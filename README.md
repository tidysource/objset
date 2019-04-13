# objset
Sets a deep value within object.
This is a mutable function, meaning the input object will be modified.

```javascript
let objSet = require('objset');

objSet({}, 'a', '/', 1);    //{a:1}

objSet({}, 'a/b', '/', 1);  //{a:{b:1}}

objSet({a:{b:1}}, 'a/c', '/', 2); //{a:{b:1, c:2}}
```
