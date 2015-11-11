# ObjectNotation
The simplest object notation

# Syntax
```javascript
// normal attributes
 name: value
 name: v1, v2
 name: , v2, ,,, vn
 name: ;
 // value element
 name;
 // multiple value elements
 n1, n2, n3;
 // normal elements
 name {...}
 name {...}{...}
 // empty elements
 name {}
 name {}
 // nested names
 n1: n2: n3: value(s)
 n1: n2: n3 {...}({...})
 n1: n2: n3 {} ({})
 // multiple names
 n1, n2, n3: value(s)
 n1, n2, n3 {...} // only one element
 n1, n2, n3 {} // only one empty element
 // multiple names must be the last part of nest names
 key1: key2: key3: n1, n2, n3: value(s)
 key1: key2: key3: n1, n2, n3: {...}
 key1: key2: key3: n1, n2, n3: {}

```
