# S-Mart Web Application

S-Mart is a simple and user-friendly web application built for managing products, customers, and orders efficiently. It is developed using **HTML, CSS, JavaScript, Java, Spring Boot, Hibernate, and MySQL**. This project demonstrates a complete full‑stack workflow with backend APIs, database integration, and a clean UI.

---

## 🚀 Features

* Add New Users (User Registration)
* Sell Items to Users
* User Login & Basic User Panel
* Admin Panel to Manage:

  * User Details
  * Orders
  * Feedback
* Responsive UI using HTML, CSS, JS
* REST APIs using Spring Boot
* Hibernate ORM for database operations
* MySQL for data storage
* Clean and structured backend & frontend folder system

---

## 🛠️ Technologies Used

### **Frontend:**

* HTML
* CSS
* JavaScript

### **Backend:**

* Java
* Spring Boot
* Hibernate

### **Database:**

* MySQL

### **Tools:**

* IntelliJ / Eclipse
* MySQL Workbench
* Postman (for testing APIs)
* Git & GitHub

---

## 📁 Project Structure

```
s-mart/
│
├── frontend/
│   ├── index.html
│   ├── styles.css
│   └── script.js
│
├── backend/
│   ├── src/main/java/com/smart/
│   │   ├── controller/
│   │   ├── entity/
│   │   ├── repository/
│   │   └── service/
│   ├── src/main/resources/
│   │   └── application.properties
│
├── database/
│   └── smart.sql
│
└── README.md
```

---

## ⚙️ How to Run the Project

### **1. Clone the Repository**

```
git clone https://github.com/amrutasuryavanshi78-create/s-mart.git
```

### **2. Configure Database**

Create a MySQL database:

```
CREATE DATABASE smart;
```

Update `application.properties`:

```
spring.datasource.url=jdbc:mysql://localhost:3306/smart
spring.datasource.username=root
spring.datasource.password=yourpassword
spring.jpa.hibernate.ddl-auto=update
```

### **3. Run Backend (Spring Boot)**

* Open project in IntelliJ/Eclipse
* Run the main application file:

```
SmartApplication.java
```

### **4. Run Frontend**

Just open `index.html` in the browser.

---

## 📌 API Endpoints (Examples)

### **Products**

```
POST   /api/products
GET    /api/products
GET    /api/products/{id}
PUT    /api/products/{id}
DELETE /api/products/{id}
```

---

---

## 📦 Future Enhancements

* Add authentication (JWT/Login)
* Add admin dashboard
* Add charts & analytics
* Deploy on cloud

---

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you'd like to change.

---

## 📄 License

This project is open-source. You can modify and use the code as needed.

---

## 👤 Author

**Amruta Suryawanshi**
GitHub: [https://github.com/amrutasuryavanshi78-create](https://github.com/amrutasuryavanshi78-create)


