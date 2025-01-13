Visitor Management System (VMS)
===============================

This project is a Full-Stack Visitor Management System application built with a Spring Boot backend and a React frontend. It provides a simple interface for managing visitor check-ins and check-outs in a workplace environment.

Features:
- Visitor check-in and check-out
- List of all visitors with their details
- Basic styling for improved user experience

Tech Stack:
- Backend: Spring Boot 2.6.3, Java 11
- Frontend: React 18
- Database: MySQL
- Build Tool: Maven

Setup Instructions:
-------------------

1. Backend Setup:
   a. Ensure you have Java 11 and Maven installed on your system.
   b. Set up MySQL and create a database named 'vms_dev'.
   c. Update the database connection details in 'src/main/resources/application-dev.properties' if necessary.
   d. Navigate to the project root directory and run:
      mvn spring-boot:run

2. Frontend Setup:
   a. Ensure you have Node.js and npm installed on your system.
   b. Navigate to the 'frontend' directory.
   c. Install dependencies by running:
      npm install
   d. Start the development server:
      npm start

3. Accessing the Application:
   Open your web browser and go to http://localhost:3000

Project Structure:
------------------

/visitor-management-system
├── src/main/java/com/example/visitormanagementsystem/
│   ├── controller/
│   │   └── VisitorController.java
│   ├── model/
│   │   └── Visitor.java
│   ├── repository/
│   │   └── VisitorRepository.java
│   ├── service/
│   │   └── VisitorService.java
│   └── VisitorManagementSystemApplication.java
├── src/main/resources/
│   ├── application.properties
│   ├── application-dev.properties
│   └── application-prod.properties
├── frontend/
│   ├── src/
│   │   ├── App.js
│   │   └── App.css
│   └── package.json
├── pom.xml
└── README.txt

Development:
------------
- The backend runs on http://localhost:8080
- The frontend development server runs on http://localhost:3000
- API requests from the frontend are proxied to the backend

Future Enhancements:
--------------------
- User authentication and authorization
- Photo capture for visitors
- ID badge printing
- Email notifications to hosts
- Reporting and analytics dashboard
- Document signing functionality

For any issues or suggestions, please contact the development team.

Happy coding!

