# Basic routing
Each route can have one or more handler functions, which are executed when the route is matched.

Route definition takes the following structure:
```
app.METHOD(PATH, HANDLER)
```
Where:

* app is an instance of express.
* METHOD is an HTTP request method, in lowercase.
* PATH is a path on the server.
* HANDLER is the function executed when the route is matched.