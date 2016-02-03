#Examination 2

##Sticky Snippets

In this assignment, you will use [Node.js](https://nodejs.org/en/), [Express.js](http://expressjs.com/) and [Mongoose](http://mongoosejs.com/) to create a web application for persistent handling of [snippets](https://en.wikipedia.org/wiki/Snippet_(programming)). The application must have full CRUD functionality regarding snippets, whereby a user must be able to create, read, update and delete snippets.

Anonymous users will only be able to view snippets. Authenticated users, in addition to view, must also be able to create, edit and delete snippets.  Because of this the application must support some basic authentication and authorization. Only use of the session store, using the [express-session](https://github.com/expressjs/session) module, is allowed for implementation of authentication and authorization. You must not use any modules like Passport, etc., to authenticate or authorize.

A user must be able to register themselves and must be able to log on to the application after entering a user ID and a password. A user cannot choose an already existing user ID as user ID is unique for the application. A user must be able to logout from the application it has already logged on.
