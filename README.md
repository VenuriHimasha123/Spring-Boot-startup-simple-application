# 🚀 ICET Demo – Spring Boot Application

A clean and minimal **Spring Boot** application built with **Java 17** and **Maven**.  
This project demonstrates the structure of a simple Spring Boot application using Controller, Service, and Model layers — ideal for learning and academic demos.

---

## 🌟 Features

- ✔️ Spring Boot entry point (`Main.java`)
- ✔️ REST API example (`StudentController`)
- ✔️ Separate service layer (`StudentService`)
- ✔️ Simple model class (`Student`)
- ✔️ Maven-based project
- ✔️ Easy to run in IntelliJ IDEA

---

## 🛠️ Tech Stack

| Component     | Version |
|--------------|---------|
| Java         | 17+     |
| Spring Boot  | (Based on your pom.xml) |
| Maven        | 3.6+    |
| IntelliJ IDEA| Recommended |

---

## 📁 Project Structure

```
icet-demo/
│
├── pom.xml                        # Maven build descriptor
│
├── src/
│   ├── main/
│   │   ├── java/edu/icet/demo/
│   │   │   ├── Main.java              # Application entry point
│   │   │   ├── Student.java           # Domain/model class
│   │   │   ├── StudentController.java # REST API controller
│   │   │   └── StudentService.java    # Service layer
│   │   │
│   │   └── resources/
│   │       └── application.properties # App configuration (optional)
│   │
│   └── test/java/                   # Unit tests
│
└── target/                          # Build output directory
```

---

## 📦 Build Instructions

### 🔨 Standard build
```sh
mvn clean package
```

### 🔄 Build with dependency update
```sh
mvn clean install -U
```

---

## ▶️ How to Run the Application

### Using IntelliJ IDEA
1. Open IntelliJ IDEA
2. Go to **File → Open**
3. Select the folder: `icet-demo`
4. Ensure **Project SDK = Java 17**
5. Open:
   ```
   src/main/java/edu/icet/demo/Main.java
   ```
6. Click the **Run (▶️)** button

The application will start and run on:

```
http://localhost:8080/
```

---

## 📡 Example API Endpoints

If you have mappings inside `StudentController`, they may look like:

```
GET  http://localhost:8080/students
POST http://localhost:8080/students
```

(Modify based on your controller.)

---

## 💡 Useful Maven Commands

| Command | Description |
|--------|-------------|
| `mvn clean` | Removes build files |
| `mvn package` | Builds a JAR file |
| `mvn install` | Installs artifacts locally |
| `mvn spring-boot:run` | Runs the app directly |
| `mvn install -U` | Updates dependencies |

---

## 🤝 Contributing

Contributions, issues, and improvements are welcome.  
You may fork the project and submit pull requests.



