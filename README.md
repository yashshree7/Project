# Learner Management System (LMS)

## Overview
The Learner Management System (LMS) is a web-based application designed to manage students, courses, and instructors efficiently. It provides functionalities for student enrollment, course management, and role-based access control. The frontend is developed using Angular, while the backend is built with Spring Boot, with MySQL as the database.

## Features
- **User Authentication:** Secure login and role-based access for admin and learner.
- **Student Management:** Add, update, view, and delete learner records.
- **Add learner System:** Admin can add learners.
- **REST API Integration:** Seamless communication between frontend and backend.

## Tech Stack
### Frontend:
- Angular
- TypeScript
- Bootstrap (for UI styling)

### Backend:
- Spring Boot
- Java
- Spring Data JPA
- MySQL

## Setup Instructions
### Prerequisites:
Ensure you have the following installed:
- Node.js and npm (for Angular)
- Angular CLI
- Java (JDK 17 or later)
- Spring Boot
- MySQL Workbench

### Installation:
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/learner-management-system.git
   ```
2. Navigate to the frontend folder and install dependencies:
   ```sh
   cd frontend
   npm install
   ```
3. Run the Angular frontend:
   ```sh
   ng serve
   ```
4. Navigate to the backend folder and run the Spring Boot application:
   ```sh
   cd backend
   mvn spring-boot:run
   ```
5. Configure MySQL database in `application.properties` (backend/src/main/resources):
   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/db11
   spring.datasource.username=root
   spring.datasource.password=root
   ```

## Usage
- **Admin**: Can manage learner.
- **Learner**: Can manage laerner list.

## API Endpoints
| Method | Endpoint            | Description                  |
|--------|---------------------|------------------------------|
| GET    | /api/students       | Get all students            |
| POST   | /api/students       | Add a new student           |
| PUT    | /api/students/{id}  | Update student details      |
| DELETE | /api/students/{id}  | Delete a student            |
| GET    | /api/courses        | Get all courses             |
| POST   | /api/courses        | Add a new course            |

## Contribution
Contributions are welcome! Feel free to open an issue or submit a pull request.

