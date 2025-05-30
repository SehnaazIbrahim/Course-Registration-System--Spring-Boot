# Course-Registration-System--Spring-Boot
# 📚 Course Registration System

A simple full-stack web application built using **Spring Boot**, **MySQL**, **HTML**, **CSS**, and **JavaScript**.  
This project allows users to register for courses, view available courses, and see a list of enrolled students through a clean and user-friendly interface.

---

## ✨ Features

- 📋 Register for a course with name, email, and course selection  
- 📖 View all available courses dynamically fetched from the database  
- 👥 Display enrolled students and their registered courses  
- 🔗 Data interactions handled via REST APIs built with Spring Boot  

---

## 🛠️ Tech Stack

### Frontend
- HTML  
- CSS  
- JavaScript (Vanilla)  

### Backend
- Spring Boot (Java)  
- Spring Data JPA  
- MySQL  

---

## 📁 Project Structure
course-registration-system/
├── backend/
│ ├── src/
│ ├── pom.xml
│ └── application.properties
├── frontend/
│ ├── index.html
│ ├── register.html
│ ├── availcourses.html
│ ├── enrolled.html
│ ├── myscript.js
│ └── style.css (if separated)
├── README.md

---

## 🚀 How to Run the Project

### Backend (Spring Boot)

1. Open the `backend/` folder in your IDE (like IntelliJ or Eclipse)
2. Update the `application.properties` file with your MySQL credentials:
spring.datasource.url=jdbc:mysql://localhost:3306/your_database_name
spring.datasource.username=your_username
spring.datasource.password=your_password



3. Run the `CourseRegistrationApplication.java` main class.

### Frontend (Static HTML/JS)

1. Open the `frontend/index.html` in your browser.
2. Make sure the backend server is running on `http://localhost:8080` for the API calls to work properly.

---

## 📸 Screenshots


 **Course Registration Page**  
![image](https://github.com/user-attachments/assets/8b8d6e02-bbc0-47cd-875d-9e6200212b99)


- **Available Courses Page**  
 
- **Enrolled Students Page**  



## 🌱 Future Enhancements 
- Add course search and filter functionality  
- Add authentication for admin and users  
- Add pagination for enrolled students and courses  
- Export enrollment data as CSV or Excel  
- Deploy the project online (Render / Railway / AWS / EC2)  

---

## 📜 License

This project is open-source and available for educational and personal use.

---

## 🙌 Acknowledgments

Thanks to the developers of **Spring Boot**, **MySQL**, and the open-source community for providing tools and frameworks that made this project possible.
