
# User Registration System

A **User Registration System** built with **JSP, Servlets, JDBC, and MySQL**, using **Bootstrap** for styling. This mini-project allows users to register by providing their details, which are stored in a MySQL database.

---

## 🚀 Features
- 📄 **JSP & Servlets**: Handles user registration and database operations.
- 💾 **MySQL Database**: Stores user details securely.
- 🎨 **Bootstrap 4.5**: Provides a responsive and modern UI.
- 🔒 **Form Validation**: Ensures required fields are filled before submission.
- ✅ **JDBC Integration**: Connects Java with MySQL for data insertion.
- 📡 **Apache Tomcat 10**: Runs the web application.

---

## 📂 Project Structure
```
/UserAuthSystem
│── src/main/java/in/sp/backend/Register.java   # Servlet handling user registration
│── webapp/
│   ├── register.jsp                            # Registration form UI
│   ├── WEB-INF/
│── pom.xml (if using Maven)
│── README.md                                   # Project documentation
```

---

## 🛠️ Technologies Used
- **Frontend**: HTML, CSS, Bootstrap 4.5, JavaScript
- **Backend**: JSP, Servlets (Jakarta EE)
- **Database**: MySQL
- **Server**: Apache Tomcat 10
- **Tools**: Eclipse, MySQL Workbench, JDBC

---

## 📌 Installation & Setup

### 1️⃣ Clone the Repository


### 2️⃣ Configure Database
- Create a **database** in MySQL:
```sql
CREATE DATABASE reg_db;
USE reg_db;

CREATE TABLE users (
    name VARCHAR(255) NOT NULL,
    email VARCHAR(255) PRIMARY KEY,
    password VARCHAR(255) NOT NULL,
    gender VARCHAR(10) NOT NULL,
    city VARCHAR(100) NOT NULL
);
```
- Update **database credentials** in `Register.java`:
```java
Connection con = DriverManager.getConnection("jdbc:mysql://localhost:3306/reg_db", "root", "yourpassword");
```

### 3️⃣ Run the Project
- Open **Eclipse**, import the project.
- **Run on Apache Tomcat 10**.
- Open in browser:  
  **`http://localhost:8080/UserAuthSystem/register.jsp`**

---

## 📷 Screenshots

### **🎨 Registration Page**
![Registration Form](your-screenshot-url)

### **📝 User Registered Successfully**
![Success Message](your-screenshot-url)

---

## 🤝 Contributing
Feel free to **fork** this repository and improve it! Contributions are welcome.  
If you find a bug, create an **issue** or submit a **pull request**.

---

## 📝 License
This project is **open-source** and available under the **MIT License**.



## ✅ Next Steps (Future Enhancements)
- 🔐 **Password Hashing** for better security.
- 📧 **Email Verification** using JavaMail API.
- 🔄 **Login System** with authentication.
- 🌍 **Deploy on AWS / Heroku** for global access.



**⭐ Star this repository** if you found it useful! 😊🚀  
Let me know if you need any modifications! 🔥


