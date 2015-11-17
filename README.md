# ObjectNotation
The Object Notatin(<b>ON</b>) is a base syntax framework which contains a series of applications.

ON's syntax is dead simple, the most simple form is just like the plain old c structure.

ON contains a powerful parser for reading source text, producing structured tree event streams. Client is responsible  for generating, or translating to target model. It can be widely used to build languages, tools, and frameworks. There are some client applications, such as OSOM, ONANT, ON-Spring.

# History
The Object Notation inspired by JSON in 2006. The biggest movitation is the quote. My thought is, the string contians quote chars, the time loss of one person writing the quote chars is not a problem.Nevertheless, it's a big problem when the whole world write the quote chars. So I tried to advise JSON to remove the quote, but I failed. Indeed ,the removing of quote means that the JSON syntax need to add more kinds of string form.

At the same time, Dan Yodler, I found him at ajaxian.com doing some similar work.

And YAML seems like. YAML is a little bit more complicated, and in the javascript word the jslint is very popular, so YAML-like cannot be linted.

And the W3 CSS seems like.

Another concept in the Object Notation is the nest path, or nest key, f.e. key1: key2: key3: value;

And from the apache's ANT practice, the default value concept is great.

And from OSGi, some http header syntax is great.

So the nest path concept emerges in the Object Notation syntax, which seems like Object world Person.friend.name, or XPath person/friend/name.


# Syntax
## Symbols
As a framework,Object Notation uses a few symbols by a extendable form.
A typical example, [OSOM](https://github.com/lyrachord/OSOM)(Original Structured Object Model, pronounce ['ɔsəm] same as awesome) use follow symbols
```
, : ; {} ' " ` /* */ //
```
In language tools cases, more symbols can be employed, such as
```
<> [] ()
```
In most DOM-like cases, two braces {} is just enough.

### Difference with JSON
JSON use brackets [] represent array. In ON's common case, there is no [], the braces with comma is enough.

Strictly speaking, ON is a superset of JSON-like, YAML included as well.

## Structure
Object Notation use the form like plain old C structure.
```
/*
root object, the document object
*/
key: value; //key value pair separated byte COLON, end with SEMI(or semicolon)
nest {
  key: value;
}
```
## Components
### String
### Comments
### Array
### nest object

