# mean_crud
http://adrianmejia.com/blog/2014/10/01/creating-a-restful-api-tutorial-with-nodejs-and-mongodb/

This tutorial uses the express generator to build out an express backend that has a users database. There is no front end. The user must use Postman
in order to query the server. The application is located at:

https://mean-crud-cornjacket.c9users.io/todos

I used nodemon so that I could refactor and test without needing to quit and restart the server.
>npm install nodemon -g

This is the database schema object

{
    "_id": "5652ae29a0db1fdd0ea6f41e",
    "name": "David",
    "note": "Hey Now",
    "completed": false,
    "__v": 0,
    "updated_at": "2015-11-23T06:11:53.364Z"
}