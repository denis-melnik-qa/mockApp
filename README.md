# mockApp
A Java-based stub (mock service) built with Spring Boot and Maven.
The stub implements a REST API with GET and POST methods:
- **GET** returns a static JSON: `{"login":"Login1","status":"ok"}`
- **POST** accepts a JSON body with two parameters (`login`, `password`) and returns a JSON containing `login`, `password`, and the current date in the format `yyyy-MM-dd HH:mm:ss`.
