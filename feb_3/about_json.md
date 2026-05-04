A client(user) send request to the server.
that request contains some of our data.

How does the request goes there?

earlier before JSON(JavaScript Object Notations), we were using XML.
XML is not easily understandable, but JSON provides proper readbility.

Every programming language supports and understands JSON. 

- We send the request to the server, and server send us response.
- json isn't only clien't server, it can also work from server to server.

Raw format : JSON format is commonly called as raw format.

How does it contains data?
- It is basically an object of key-value pairs.

we can also use JSON files as a module and require inside another file.
one JSON file can use another.

~About Parse - it is a function that helps to convert the JSON object into JavaScript format.
~About toStringify - it is a function that helps to convert the JavaScript object into JSON.

How to JSON?
1. The content inside JSON is wrapped inside curly braces.
2. A key must be string, however a value can be anything like array, another object, null, string, number, etc.
    for ex - "key" : value
3. Differnt key value pairs are seperated by comma.
4. 






How does JSON data look like

{
    "id" : 101,
    "Name": "user",
    "isActive": true,
    "languages": ["English", "Hindi"],
    "techStack": {"Primary": "PHP", "Secondary": "Heap"},
    "isPlaced": null
}

















