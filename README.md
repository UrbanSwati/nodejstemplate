# NodeJS Project Template incl JWT

1. npm install
2. npm start
3. Register user (POST: localhost:5000/api/register)
4. Login (POST: localhost:5000/api/login) copy token from response
5. Test Auth by adding `Authorization` in headers with `bearer + token` (GET: localhost:5000/api/test) NB: replace the string token with the token recieved to you after you have logged in
Example:
```
bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjViZjNhMzhjN2M0MDE1Mjk4NmExZTY1NSIsImVtYWlsIjoiaGVsbG9AZ21haWwuY29tIiwiaWF0IjoxNTQyNjkzOTU1LCJleHAiOjE1NDI2OTQxNTV9.k6-RfMtc2xomK
```

# Starting Project from nada
1. `npm init -y` to create npm package file
2. Install dependences for server 
    `npm install express jsonwebtoken mongoose mongose passport passport-jwt cors body-parser bcrypt` 
3. add `start` field in the scripts, for live reload add `nodemon` globally on your machine
