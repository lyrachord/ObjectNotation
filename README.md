# ObjectNotation
The simplest object notation

# Syntax
// normal attributes <br>
 name: value<br>
 name: v1, v2<br>
 name: , v2, ,,, vn<br>
 name: ;<br>
 // value element<br>
 name;<br>
 // multiple value elements<br>
 n1, n2, n3;<br>
 // normal elements<br>
 name {...}<br>
 name {...}{...}<br>
 // empty elements<br>
 name {}<br>
 name {}<br>
 // nested names<br>
 n1: n2: n3: value(s)<br>
 n1: n2: n3 {...}({...})<br>
 n1: n2: n3 {} ({})<br>
 // multiple names<br>
 n1, n2, n3: value(s)<br>
 n1, n2, n3 {...} // only one element<br>
 n1, n2, n3 {} // only one empty element<br>
 // multiple names must be the last part of nest names<br>
 key1: key2: key3: n1, n2, n3: value(s)<br>
 key1: key2: key3: n1, n2, n3: {...}<br>
 key1: key2: key3: n1, n2, n3: {}<br>
