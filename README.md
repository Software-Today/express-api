# Simple CRUD API
A simple backend API with full CRUD functionality.

![alt text](https://github.com/ChrisFAlvarenga/node-express-api/blob/main/image.png?raw=true)

## Description
Performs the four primary operations in databases: Create, Read, Update, and Delete.
* Create(C): Create or add new entries.
* Read(R): Read, retrieve, search, or view entries.
* Update(U): Update, or edit existing entries.
* Delete(D): Delete, deactivate, or remove existing entries.

We use the following HTTP methods to perform the various CRUD operations
* GET: Reads the data in our database.
* POST: Creates new resources in the database.
* PATCH: It updates the data in the database. It takes parameters to identify the specific entry. It updates only the specified content of the specific entry.
* DELETE: Deletes the data in the database. It takes parameters to identify the specific entry.

We use [NODE.js](https://nodejs.org/en/) and [Express](https://expressjs.com/) to achieve this as well [uuid](https://www.npmjs.com/package/uuid), to create unique ids for our entries and [nodemon](https://www.npmjs.com/package/nodemon), which allows us to make and see changes without having to manually restart the server.

Through the browser we are able to make get requests, however, to make any write requests we have to use a program such as [Postman](https://www.postman.com/). Using the program we are able to make write requests such as post, patch, and delete. 

Note: Our implementation uses a mock database. Entries will be deleted when the server is shutdown.

## Roadmap
Possible ideas for future releases would be
* Use a database such as [MongoDB](https://www.mongodb.com/). This would allow us to keep data in between session.
* Implement all HTTP methods.

## Acknowledgment
[JavaScript Mastery](https://www.youtube.com/watch?v=l8WPWK9mS5M) for a great video tutorial to help understand and learn how to implement a CRUD API with [NODE.js](https://nodejs.org/en/) and [Express](https://expressjs.com/).

[Subodh Poudel](https://www.becomebetterprogrammer.com/complete-guide-to-build-a-crud-api-with-node-js-and-mongodb/[Subodh) for an excellent article explaining what is a CRUD API and explains how to implement [MongoDB](https://www.mongodb.com/).

[Speak_](https://speak.careers/) for the idea and encouragement to create this project.
