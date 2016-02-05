# CPSC 113 Social To-Do App by Tanya Shi

This application allows users to create tasks, add collaborators, and mark them as
complete. It is built using a stack comprising of MongoDB, Express.js, and Node.js. 

## How to run this

You can run the server with 

    nodemon index.js
    SESSION_SECRET='' MONGO_URL="mongodb://localhost:27017/social-todo" ./node_modules/.bin/nodemon index.js

This app was built with the help of starting code from [Kyle Jensen](https://github.com/kljensen/cpsc113-social-todo-node).