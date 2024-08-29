# mern-todo-backend

Documentation for mern-todo-app:

Deployed link using vercel : https://mern-todo-frontend-beige.vercel.app

Can run backend on a local machine and connect mongoDB to localhost : 'mongodb://localhost:27017/todoDB' and it runs successfully


BACKEND:

1. Need to have:
   
  Node.js and npm installed on your machine.
  MongoDB instance (local or MongoDB Atlas). (I did not use mongoDB atlas because the cluster was taking too long to create).

2. Project Structure:

  mern-todo-backend/

  ├── controllers/

  │   └── todoController.js

  ├── models/

  │   └── Todo.js

  ├── routes/

  │   └── todoRoutes.js

  ├── .env

  ├── index.js

  └── package.json

3. Clone both the repository (I do not know how to use 1 repository for both frontend and backend yet):

  git clone https://github.com/Slashin3/mern-todo-backend

  cd backend

4. npm start


5. Endpoints


GET - api/todos

POST - api/todos

DELETE - api/todos:id

FRONTEND:
Built using react

1. Project Structure

  mern-todo-frontend/

  ├── public/

  │   └── index.html

  ├── src/

  │   ├── components/

  │   │   └── TodoList.js

  │   ├── App.css

  │   ├── App.js

  │   ├── index.js

  ├── package.json

  └── .env

2. Steps:


  cd mern-todo-frontend

  npm install

  npm start

It will start on "localhost:3000"

MongoDB Connection string:
Replace MongoDB connection string using the 'mongodb://localhost:27017/todoDB' or any other connection string using mongoDB atlas.
