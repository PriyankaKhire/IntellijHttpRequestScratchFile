
# Intellij HTTP Request Scratch files
A simpler alternative to postman

## What are scratch files
Scratch files can be used to test HTTP requests during development. </br>
Scratch files are not stored inside a project, so IntelliJ IDEA can modify them and add additional information about the request. 

## Creating the file
Press ⇧ ⌘ N and select HTTP Request. </br>
<img src="img/Creating Scratch File.png" height="300" width="300">

## Format of Scratch file
### POST
```http
# Method Request-URI HTTP-Version
POST http://localhost:PortNumber/uri/of/api
Content-Type: application/json
# Header-field: Header-value
Authorization: Bearer Token Value

{
    #Request-Body
    "key1": "value1",
    "key2": "value2",
}
```
Note: Always make sure Content-Type is present. </br>
<img src="img/Example POST request.png" height="220" width="500">

## Good Reads
<a href="https://www.jetbrains.com/help/idea/http-client-in-product-code-editor.html">HTTP Client</a></br>
<a href="https://www.jetbrains.com/help/idea/exploring-http-syntax.html">Exploring the HTTP request syntax</a>

      
    

