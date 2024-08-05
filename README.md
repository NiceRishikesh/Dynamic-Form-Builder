# Form Management Application

This is a Form Management Application built with a MERN (MongoDB, Express, React, Node.js) stack. The application allows users to create, read, update, and delete (CRUD) forms with various input fields.

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Running the Application](#running-the-application)
- [API Endpoints](#api-endpoints)
- [Folder Structure](#folder-structure)

## Features

- Create new forms with various input fields.
- Read existing forms.
- Update forms by ID.
- Delete forms by ID.

## Tech Stack

- Frontend: React
- Backend: Node.js, Express
- Database: MongoDB

## Installation

### Prerequisites

- Node.js (>=14.x)
- npm (>=6.x)
- MongoDB (>=4.x)

### Backend Setup

1. Clone the repository:
   ```sh
   git clone https://github.com/NiceRishikesh/Dynamic-Form-Builder.git 
    
2. Install backend dependencies:

    ```sh
    npm install
      
3. Set up environment variables:
    Add your db string in the dbConn.js:

    ```sh
     const MONGODB_URL = <your_mongodb_connection_string>

4. Start the backend server using nodemon:

    ```sh
    Copy code
    npx nodemon


### Frontend Setup

1. Navigate to the frontend directory:

  ```sh
    cd ../frontend
    Install frontend dependencies:
   ```


2. Install frontend dependencies:
  ```sh
    npm install
  ```



3. Start the frontend development server:

```sh
npm run dev
 ```


### API Endpoints
  Form Routes
 * GET /api/v-1//all-forms: Get all forms.
 * POST /api/v-1/forms: Create a new form.
 * POST /api/v-1/get-form-by-id: Get a form by ID.
 * PUT /api/v-1/update-form: Update a form.
 * DELETE /api/v-1/delete-form: Delete a form.

## Acknowledgments

Crafted with ❤️ by Hrashikesh Pandey
