1.HTTPS1 vs HTTPS2
HTTP1
HTTP2
For every transfer control protocol only request can be send
From HTTP2 we can send multiple requests to sever to get data in same time
It can Define 16 status codes; the error prompt is not specific
Underlying semantics of HTTP such as headers,status codes remains the same
It is text based protocol so it can readable
It is binary protocol
Provides support for caching to deliver pages faster
Removes the need for unnecessary optimization hacks.


2.Objects and its internal representation in JS

Objects, in JavaScript, is it’s most important data-type and forms the building blocks for modern JavaScript. These objects are quite different from JavaScript’s primitive data-types(Number, String, Boolean, null, undefined and symbol) in the sense that while these primitive data-types all store a single value each (depending on their types).Objects are more complex and each object may contain any combination of these primitive data-types as well as reference data-types.An object, is a reference data type. Variables that are assigned a reference value are given a reference or a pointer to that value. That reference or pointer points to the location in memory where the object is stored. The variables don’t actually store the value.Loosely speaking, objects in JavaScript may be defined as an unordered collection of related data, of primitive or reference types, in the form of “key: value” pairs. These keys can be variables or functions and are called properties and methods, respectively, in the context of an object.   For Eg. If your object is a car, it will have properties like name, age, address, id, etc and methods like colour,model,chasis number etc.
Syntax: 

Var car = { colour : “Red”,
 model : “BMW R”,
 chasis_number : “2019t109”};
