# CRUD Backend

## 📌 Overview
This project is a backend application designed to perform CRUD (Create, Read, Update, Delete) operations. It is built using **Java** and **Spring Boot**, following best practices for RESTful API development.

## 🚀 Features
- Fully functional RESTful API
- Create, Read, Update, and Delete operations
- Uses **Spring Boot** for backend development
- **Maven** for dependency management
- Structured codebase with MVC architecture
- Can be easily extended for additional features

## 🛠️ Tech Stack
- **Language:** Java
- **Framework:** Spring Boot
- **Build Tool:** Maven
- **Database:** (db4free.net - MySQL Database for free)
- **Tools:** Postman (for API testing), Git (for version control)

## 📂 Project Structure

```bash
CRUD-backend/
│-- src/
│   ├── main/
│   │   ├── java/com/example/frontcrud/
│   │   │   ├──config/               # Configurations
│   │   │   ├── controller/          # Contains API controllers
│   │   │   ├── service/             # Business logic
│   │   │   ├── repository/          # Database interactions
│   │   │   ├── entities/            # Data models
│   ├── resources/
│   │   ├── application.properties   # Configuration file
│-- pom.xml  # Maven dependencies
```

## 🔧 Installation & Setup
Follow these steps to set up and run the project:

### 1️⃣ Clone the Repository
```
git clone https://github.com/shubham-vandara/CRUD-backend.git

cd CRUD-backend

```
### 2️⃣ Build the Project
```

mvn clean install

```
### 3️⃣ Run the Application
```

mvn spring-boot:run

```
