# Task Management System

A **Task Management System** built using **Spring Boot, Spring Security, MySQL, and JWT** to efficiently manage tasks and projects with role-based access control.

## Features
- Admin can add projects and assign them to project managers.
- Project managers can assign tasks to employees and track their progress.
- Employees can update task status in real time.
- Secure authentication and authorization using JWT.
- RESTful API implementation for seamless interaction.

## Getting Started

### Prerequisites
Ensure you have the following installed:
- Java 17+
- Spring Boot
- MySQL
- Maven

### Installation & Setup

#### 1. Clone the Repository
```sh
git clone https://github.com/arpiitt/task-management-system.git
cd task-management-system
```

#### 2. Configure the Database
Update `application.properties` or `application.yml` with your MySQL credentials:
```properties
spring.datasource.url=jdbc:mysql://localhost:3306/task_management
spring.datasource.username=root
spring.datasource.password=yourpassword
spring.jpa.hibernate.ddl-auto=update
```

#### 3. Build and Run the Application
```sh
mvn clean install
mvn spring-boot:run
```

The application will start at `http://localhost:8080`.

### API Endpoints
Refer to the API documentation (Swagger or Postman collection) for available endpoints.


## Contributing
Feel free to fork this repository and create a pull request with improvements!

## License
This project is licensed under the MIT License.

---
Happy Coding! 🚀
