Middleware in Express.js
Middleware is a function that runs between the request and the response in an Express application.

Whenever a user sends a request to the server, middleware gets executed before the final route handler.

How does middleware work?
1. User sends a request to the server.
2. Middleware gets executed.
3. Middleware performs some tasks.
4. next() passes control to the next middleware or route.
5. Finally, the server sends a response to the user.

Why do we use middleware?
- To check whether a user is logged in.
- To check authentication.
- To log user requests.
- To handle errors.
- To process request data.
