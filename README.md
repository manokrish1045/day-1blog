# day-1blog
1.difference between http 1.1 vs http 2
HTTP/1.1

Ithe usest works on the textual format.	.
There is head of line blocking that blocks all the requests behind it until it doesn’t get its all resources.
It uses requests resource Inlining for use getting multiple pages
It compresses data by itself.	

HTTP/2
It works on the binary protocol
It allows multiplexing so one TCP connection is required for multiple requests.
It uses PUSH frame by server that collects all multiple pages 
It uses HPACK for data compression.



2 Object And its internal representation in JavaScript
objects in JavaScript may be defined as an unordered collection of related data, of primitive or reference types, in the form of “key: value” pairs. These keys can be variables or functions and are called properties and methods, respectively, in the context of an object.

For Eg. If your object is a student, it will have properties like name, age, address, id, etc and methods like updateAddress, updateNam, etc.
