# Employee Management System

A simple Spring Boot REST API project to perform CRUD operations on Employee data using MySQL.

---

## 🚀 Tech Stack
- Java 17+
- Spring Boot
- Spring Data JPA
- MySQL
- Maven
- Lombok

---

## 📌 Features
- Create Employee
- Get All Employees
- Get Employee by ID
- Update Employee
- Delete Employee
- Exception Handling
- Input Validation

---

## ⚙️ Database Configuration (application.properties)

spring.datasource.url=jdbc:mysql://localhost:3306/employee_db  
spring.datasource.username=root  
spring.datasource.password=yourpassword  

spring.jpa.hibernate.ddl-auto=update  
spring.jpa.show-sql=true  

---

## 🌐 API Endpoints

POST    /api/employees  
GET     /api/employees  
GET     /api/employees/{id}  
PUT     /api/employees/{id}  
DELETE  /api/employees/{id}  

---

## 📬 Sample JSON

{
  "name": "Ravi Kumar",
  "email": "ravi.kumar@gmail.com",
  "salary": 50000
}

---

## ▶️ Run Application

mvn spring-boot:run  

Server: http://localhost:8080

---

## 👨‍💻 Author
Poovarasan
