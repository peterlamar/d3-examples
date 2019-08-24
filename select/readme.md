https://www.d3indepth.com/selections/


1. Select always returns an object, an empty object with null inside if not found

```
d3.select('test')
qa {_groups: Array(1), _parents: Array(1)}
    _groups: Array(1)
        0: [null]
        length: 1
        __proto__: Array(0)
    _parents: [html]
    __proto__: Object
d3.select('circle')
qa {_groups: Array(1), _parents: Array(1)}
    _groups: Array(1)
        0: [circle]
        length: 1
        __proto__: Array(0)
    _parents: [html]
    __proto__: Object
```
