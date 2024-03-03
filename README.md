# Customer Management App
Zithara Technologies 
Round 2 - Task: React and Node JS Application Development. 
This is a simple customer management app built with React, Node.js, Express and PostgreSQL.
## Features
• Displays customer data in a paginated table
• Search customers by name and location
• Sort customers by created date and time
• React frontend with Node/Express backend
• PostgreSQL database with dummy seeded data
## Usage
Create a .env file in then root and add the following
DB_HOST = localhost
DB_PORT = 5432
DB_USER = postgres
DB_PASS = admin
DB_NAME = customerdb
## Install Dependencies
• npm install
• cd frontend
• npm install 
## Frontend
The frontend directory has the React frontend code. It uses React hooks for state management and Axios to call APIs.
Some key files:
• App.js - Handles routing and layout
• customers.js - Customer table component
• API.js - Axios API calls
## Backend
The index.js has the Express code with routes.
Some key files:
• routes/index.js - API route handlers
• db/index.js - Database connection and queries
• utils/paginate.js - Pagination helper

