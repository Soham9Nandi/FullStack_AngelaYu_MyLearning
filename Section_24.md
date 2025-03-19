1. Express is like an eletric scredriver for the nails of Node.js
2. importing express from express, also make the type as module for ES6
3. we create an instance of express, called app
4. then we can listen with the help of that app
5. specify ports as a variable, so that it is accessible and changeable
6. Accessing server by tryping localhost:port
7. What is a localhost?
8. CANNOT GET\ error
9. HTTP, hypertext transfer protocol, communication between computers
10. GET -> Requests something from the server
11. POST -> Sending something to the server
12. PUT and PATCH -> Updating(replacing and patched item, respectively)
13. DELETE -> as the name suggests

14. app.get("/",(req,res) =>{
res.send("Message)})

res - response
req - request

15. nodemon installation
16. nodemon index.js
17. Endpoints, destinations

18. HTTP RESPONSE CODE MEANING
19. 1 - hold on
20. 2 - Here you go, everything is ok
21. 3- Go away- redirection
22. 4- Client side error
23. 5 - server side error


24. POSTMAN Tutorial


25. MIDDLE WARE - bridge between softwares and server
26. it can, preprocesss requests, logs requests, authentication, process and handle the errors
27. Public folder contains static elements, like html css, etc
28. bodyparser middleware npm
### Important
29. MIDDLEWARE ORDER MATTERS, because the next() actually passes the processed information to the next middleware in line and in that way we can process the data before sending it
30. express .use (the parser, the type, then extended)
31. the above gives our request a body that we can acces and read now
32. To give the form value, go to postman and then go to body and wwwformencoded and then input the values



33. Body parser belongs to preprocessing categories of middleware
34. Morgan -> logging middleware

# Creating Custom MiddleWare
1. function(req,res,next){
     some functions with res and req.
   next();
   }

res.redirect

