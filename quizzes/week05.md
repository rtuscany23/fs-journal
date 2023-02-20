# Intro to Server side concerns with JavaScript

**1.** What do the letters of the acronym `CRUD` stand for?
<!-- enter you answer in the space below -->
```
-create, read, update, delete
```
**2.** Each action that `CRUD` represents maps to an HTTP request. What HTTP request does each `CRUD` action correspond to?
<!-- enter you answer in the space below -->
```create/post, read/get, update/post, delete/delete

```
**3.** What does `ORM` stand for? Which `ORM` do we use when interacting with MongoDB
<!-- enter you answer in the space below -->
```
-object relational mapping.
```
**4.** Which two `HTTP` request types include a body?
<!-- enter you answer in the space below -->
```
-the put and post requests include bodies
```
**5.** In a/an _______ coding model, when you call a function, it returns only when the action has finished and stops your program for the time the action takes. Likewise in a/an _______ coding model, multiple things are allowed to happen at one time. When you perform an action, your program continues to run.  Fill in the blanks.
<!-- enter you answer in the space below -->
```
-async is used in concurrent programming model and allows multiple things to happen at one time. Syncronous programming will only returns when a function is finised.
```

**6.** Fill in the missing piece of this snippet of code.
```js
import schema from "mongoose"
let Schema = new.Schema;
```
<!-- enter you answer in the space below -->
```
import schema from "mongoose"
let Schema = new.Schema;
```
**7.** What is middleware?
<!-- enter you answer in the space below -->
```
middleware is a layer of software that resides between two systems, like express.js the communicates between db and the server side.
```
**8.** The ______ pipeline delivers information from the client while the ______ pipeline returns it. Fill in the blanks. 
<!-- enter you answer in the space below -->
```
-request pipleline delivers / return pipeline returns.
```
**9.** 
Demonstrate the pattern that is used to include a request query with the client's `HTTP` request providing the property `tag` and the value `winter`.
<!-- enter you answer in the space below -->
```
http://something.com/api/datagroup?tag=winter
```