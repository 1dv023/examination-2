#Examination 2

>###Deadline
Friday, March 4, 2016 7:00 AM 
###Submission Instructions
Submit your solution, by creating a release on GitHub named “v1.0″. In case of changes after creating a release, please increment the minor version number, i.e. “v1.1″, “v1.22", etc.

##Sticky Snippets

In this assignment, you will use [Node.js](https://nodejs.org/en/), [Express.js](http://expressjs.com/) and [Mongoose](http://mongoosejs.com/) to create a web application for persistent handling of [snippets](https://en.wikipedia.org/wiki/Snippet_(programming)). The application must have full CRUD functionality regarding snippets, whereby a user must be able to create, read, update and delete snippets.

Anonymous users will only be able to view snippets. Authenticated users, in addition to view, must also be able to create, edit and delete snippets.  Because of this the application must support some basic authentication and authorization. Only use of the session store, using the [express-session](https://github.com/expressjs/session) module, is allowed for implementation of authentication and authorization. You must not use any modules like Passport, etc., to authenticate or authorize.

Users must be able to register themselves and must be able to login to the application after entering a user ID and a password. A user cannot register an already existing user ID as user ID is unique for the application. A user must be able to log off from the application it has already logged on.
