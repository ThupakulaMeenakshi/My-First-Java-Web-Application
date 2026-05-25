# My First Java Web Application

A basic Java-based web application built using **Apache Maven** and the standard `maven-archetype-webapp` template.

## 🚀 Features
* Built using Apache Maven build automation tool.
* Packaged as a standard Web Application Archive (`.war`) file.
* Lightweight development server execution configured via Jetty.

## 🛠️ Prerequisites
Before running or developing this project, ensure you have the following installed:
* **Java Development Kit (JDK)**: Version 8 or higher
* **Apache Maven**: Version 3.6.0 or higher
* **Git**: To clone/push source code

## 💻 Getting Started

### 1. Clone the Project
```bash
git clone https://github.com
cd my-First-java-WebApp
```

### 2. Compile and Build
To compile the Java source files and package the project into a `.war` file, run:
```bash
mvn clean package
```

### 3. Run Locally
You can run this application without installing an external Tomcat server by utilizing the embedded Jetty plugin:
```bash
mvn jetty:run
```
Once the console logs display `Started Jetty Server`, open your browser and navigate to:
👉 **http://localhost:8080/**

## 📁 Project Structure
```text
my-First-java-WebApp/
│
├── src/
│   └── main/
│       ├── webapp/
│       │   ├── WEB-INF/
│       │   │   └── web.xml      # Deployment descriptor
│       │   └── index.jsp        # Application landing page
│       └── java/                # Java source packages
│
├── pom.xml                      # Maven configuration file
└── README.md                    # Project documentation
```

## 📝 Technologies Used
* **Backend:** Java
* **Build System:** Apache Maven
* **Web Server (Dev):** Eclipse Jetty Plugin
