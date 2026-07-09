# Backend Development – Mission 2

## Overview

A simple REST API built using Node.js, Express.js, MongoDB Atlas, and Mongoose to perform CRUD operations on user data.

## Features

* MongoDB Atlas integration
* User schema with validation
* Create, Read, Update, Delete (CRUD)
* Error handling
* REST API endpoints

## Tech Stack

* Node.js
* Express.js
* MongoDB Atlas
* Mongoose
* Postman

## Run the Project

```bash
npm install
npm start
```

Create a `.env` file:

```env
PORT=3000
MONGO_URI=your_mongodb_connection_string
```

## API Endpoints

* `POST /users` – Create User
* `GET /users` – Get All Users
* `GET /users/:id` – Get User by ID
* `PUT /users/:id` – Update User
* `DELETE /users/:id` – Delete User
