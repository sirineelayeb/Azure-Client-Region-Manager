# Azure Client & Region Manager

A lightweight Spring Boot application demonstrating full-stack CRUD operations with Thymeleaf and REST APIs, designed for seamless deployment on **local environments**, **Azure App Service**, and **virtual machines**.

## Features

- **Client Management (CRUD)**
  - Create, read, update, and delete clients
  - Search clients by name
  - User-friendly HTML interface with Thymeleaf
- **Region Management (REST API)**
  - List all regions
  - Add new regions via POST endpoint
- Fully functional end-to-end workflow:
  - Local development & testing
  - Azure App Service deployment
  - Virtual machine deployment
- Production-ready configuration with Azure SQL Database support

## Demo Video

Watch the complete demo (Local Run → Database Setup → Azure App Service Deployment → VM Testing):  
https://drive.google.com/file/d/1wi5_vKFPOCWhBqyWQOIhgRgkj8sQlwUN/view?usp=sharing

## Technologies Used

- Spring Boot 3.x
- Spring Data JPA
- Spring Web MVC
- Thymeleaf
- Microsoft SQL Server / Azure SQL Database
- Maven
- Java 17+

## Local Setup

### Prerequisites
- Java 17 or higher
- Maven 3.8+
- Git

### Steps

```bash
# 1. Clone the repository
git clone https://github.com/sirineelayeb/azure-mini-projet.git
cd azure-mini-projet

# 2. Build the project
mvn clean install

# 3. Run the application
mvn spring-boot:run
