# Employee Management System - Frontend

This project is the frontend for a simple Employee Management System (EMS). It allows users to view, add, update, and delete employee information.

## Features

*   **List Employees:** View a list of all employees.
*   **Add Employee:** Add a new employee to the system.
*   **Update Employee:** Edit the details of an existing employee.
*   **Delete Employee:** Remove an employee from the system.

## Technologies Used

*   **React:** A JavaScript library for building user interfaces.
*   **Vite:** A fast build tool and development server for modern web projects.
*   **Axios:** A promise-based HTTP client for the browser and Node.js.
*   **Bootstrap:** A popular CSS framework for building responsive, mobile-first websites.
*   **React Router DOM:** A library for routing in React applications.

## Setup and Installation

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/sunil-gumatimath/ems-frontend.git
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd ems-frontend
    ```
3.  **Install dependencies:**
    ```bash
    npm install
    ```
4.  **Start the development server:**
    ```bash
    npm run dev
    ```
    The application will be available at `http://localhost:3000`.

## Usage

Once the application is running, you can perform the following actions:

*   **View all employees:** The main page displays a list of all employees.
*   **Add a new employee:** Click the "Add Employee" button to open a form for adding a new employee.
*   **Update an employee:** Click the "Update" button next to an employee to edit their information.
*   **Delete an employee:** Click the "Delete" button next to an employee to remove them from the system.

## API Endpoints

This frontend application consumes a backend API with the following endpoints:

*   `GET /api/employees`: Get all employees.
*   `GET /api/employees/{id}`: Get an employee by their ID.
*   `POST /api/employees`: Create a new employee.
*   `PUT /api/employees/{id}`: Update an employee.
*   `DELETE /api/employees/{id}`: Delete an employee.