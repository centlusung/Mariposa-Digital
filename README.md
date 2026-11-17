# Ely's Atsara E-Store

An online e-commerce platform designed to bring Ely's Atsara products to customers through a convenient and accessible digital shopping experience.

## Overview

**Ely's Atsara E-Store** is a full-stack web application developed to streamline the process of browsing products, managing inventory, and handling customer orders. The system provides a centralized platform for customers and administrators, supporting essential e-commerce operations through an intuitive user interface and a structured backend architecture.

The application was developed using **Angular** for the frontend and **Java Spring Boot** for the backend, following a structured approach to software engineering, requirements analysis, database design, and application development.

## Technologies Used

### Frontend
- Angular
- TypeScript
- HTML5
- CSS3
- Bootstrap

### Backend
- Java
- Spring Boot
- RESTful API Architecture

### Development Tools
- Git and GitHub
- Visual Studio Code
- Database Management Tools

## User Roles

The system implements role-based access control (RBAC) with four primary user roles:

| Role | Description |
|---|---|
| Guest | Can browse the available products and explore the store. |
| Customer | Can access customer-oriented shopping and ordering functionalities. |
| Admin | Can manage products, inventory, and relevant store operations. |
| Super Admin | Has elevated administrative privileges and oversees system management. |

## Key Features

- **Product Management** – Create, retrieve, update, and delete product records.
- **Product Catalog** – Browse and explore available atsara products.
- **Order Management** – Support the customer ordering workflow.
- **User Management** – Organize users according to their assigned roles.
- **Role-Based Access Control** – Restrict functionalities based on user permissions.
- **Database Integration** – Maintain structured data for products, customers, and orders.
- **REST API Integration** – Enable communication between the Angular frontend and Spring Boot backend.

## System Architecture

The application follows a client-server architecture:

1. **Frontend (Angular)** – Handles the user interface, navigation, and client-side interactions.
2. **Backend (Spring Boot)** – Processes business logic, application requests, and REST API operations.
3. **Database** – Stores and manages application data, including product, customer, and order information.

## Project Structure

The project is organized into two primary application components:

```text
elys-atsara/
│
├── frontend/          # Angular application
│   ├── src/
│   ├── angular.json
│   └── package.json
│
├── backend/           # Spring Boot application
│   ├── src/
│   │   ├── main/
│   │   └── test/
│   └── pom.xml
│
└── README.md
```

*Note: Adjust the folder names and structure to match the actual repository.*

## Getting Started

### Prerequisites

Make sure the following tools are installed:

- Node.js and npm
- Angular CLI
- Java Development Kit (JDK)
- Maven (if using Maven)
- A configured database

### Installation

**1. Clone the repository**

```bash
git clone <repository-url>
cd elys-atsara
```

**2. Set up the backend**

Navigate to the backend directory:

```bash
cd backend
```

Configure the database connection and application properties in `src/main/resources/application.properties`.

Run the Spring Boot application using Maven:

```bash
mvn spring-boot:run
```

**3. Set up the frontend**

Open another terminal and navigate to the frontend directory:

```bash
cd frontend
```

Install dependencies:

```bash
npm install
```

Start the Angular development server:

```bash
ng serve
```

Open your browser and navigate to:

```text
http://localhost:4200
```



## Development Objectives

This project demonstrates the practical application of software engineering principles, including:

- Requirements Engineering
- Requirements Traceability Matrix (RTM)
- Database Design and Management
- UML Modeling
- Full-Stack Web Development
- CRUD Operations
- RESTful API Development
- Software Testing and Validation

