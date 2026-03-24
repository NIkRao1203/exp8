# 📘 REST API Design Experiments & Case Study

## 🧾 Project Title
REST API Development Using Spring Boot with Student Management System

---

## 📌 Introduction
This project is developed to perform backend API design experiments using **Spring Boot**.  
It includes a case study called **Student Management System** to demonstrate how REST APIs work in a real-world application.

---

## 🎯 Objectives
- To design REST APIs using Spring Boot  
- To understand CRUD operations (Create, Read, Update, Delete)  
- To implement layered architecture (Controller, Service, Repository)  
- To test APIs using Postman  
- To build a simple Student Management backend system  

---

## ⚙️ Technologies Used
- Java  
- Spring Boot  
- Spring Data JPA  
- Hibernate  
- MySQL (or any configured database)  
- Postman  

---

## 🧪 Experiments

### 🔹 Experiment 1: Running Spring Boot Application
The Spring Boot application is successfully executed.  
Tomcat server starts on port **8080**, and Hibernate initializes JPA.

<img src="https://github.com/NIkRao1203/exp8/blob/main/Screenshots/1.png?raw=true" />
<img src="https://github.com/NIkRao1203/exp8/blob/main/Screenshots/2.png?raw=true" />
<img src="https://github.com/NIkRao1203/exp8/blob/main/Screenshots/3.png?raw=true" />
<img src="https://github.com/NIkRao1203/exp8/blob/main/Screenshots/5.png?raw=true" />

---

### 🔹 Experiment 2: POST API (Add Student)
A POST API is implemented to add student data into the database.  
The request is tested using Postman by sending JSON data.

**Sample Request:**
```json
{
  "course": "aiml",
  "id": 4,
  "name": "hi"
}
