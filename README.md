# Secure Student Management System

## Project Description
This project is a web-based application designed to manage student data securely, with integrated data analytics for insights. It features user authentication, role-based access control, and a dashboard for data visualization.

## Features
- Secure User Authentication (JWT)
- Role-Based Access Control (Admin, Teacher, Student)
- CRUD Operations for Student Records
- Data Encryption for Sensitive Information
- Data Analytics Dashboard (Charts for student performance, attendance, etc.)
- API Integration (RESTful API)
- Audit Logs for Tracking User Activity

## Technologies Used
- **Frontend:** React.js, Chart.js
- **Backend:** Node.js, Express.js, JWT for authentication
- **Database:** MongoDB with Mongoose
- **Security:** bcrypt for password hashing, SSL/TLS for secure communication

## Installation
1. **Clone the repository:**
    ```bash
    git clone [repository-url]
    ```
2. **Navigate to the project directory:**
    ```bash
    cd SecureStudentManagementSystem
    ```
3. **Install dependencies for backend:**
    ```bash
    cd backend
    npm install
    ```
4. **Install dependencies for frontend:**
    ```bash
    cd ../frontend
    npm install
    ```
5. **Run the project:**
    - Start the backend server:
      ```bash
      cd backend
      npm start
      ```
    - Start the frontend development server:
      ```bash
      cd ../frontend
      npm start
      ```

## API Documentation
- **/api/auth/login**: POST - User login
- **/api/students**: GET - Fetch all students (Admin access only)
- **/api/students/:id**: GET - Fetch a single student record
- **/api/students**: POST - Create a new student record (Admin access only)
- **/api/students/:id**: PUT - Update a student record (Admin access only)
- **/api/students/:id**: DELETE - Delete a student record (Admin access only)

## Contributions
Feel free to fork this project, open issues, and submit pull requests.

## License
This project is licensed under the MIT License.
