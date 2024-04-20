Employee Management System

The Employee Management System is a web application designed to efficiently manage employee details and operations within an organization. It provides features for administrators to add, edit, delete, and view employee information, as well as perform various administrative tasks.

Features


User Authentication: Secure login for administrators using JSON Web Tokens (JWT).

Employee Management: CRUD operations (Create, Read, Update, Delete) for employee details.

Category Management: Ability to categorize employees into different categories.

Image Upload: Allows uploading employee images for better identification.

Statistics: Provides statistics such as admin count, employee count, and total salary expenditure.

Technologies Used

Backend: Node.js with Express.js framework for server-side logic.

Database: MySQL for storing employee and category data.

Frontend: React.js with Vite for fast and efficient development.


Authentication: JWT for secure user authentication and authorization.

File Upload: Multer middleware for handling file uploads.

Getting Started

Prerequisites

Node.js installed on your machine.

MySQL database server running locally or accessible via a remote connection.

Installation

Clone the repository:

https://github.com/AkramCodeer/employeeManagement.git

Install backend dependencies:


npm install

Install frontend dependencies:

cd frontend

npm install

Running the App

Start the backend server:


nodemon index.js

This will start the backend server on port 3000.
Start the frontend development server:

npm run dev

This will start the frontend server on port 3001 and open the application in your default web browser.


Contributions are welcome! Please feel free to submit bug reports, feature requests, or pull requests.

License
This project is licensed under the MIT License - see the LICENSE file for details.


