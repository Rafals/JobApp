# 💼 JobApp - Modern Job Portal

![JobApp Screenshot](/jobpost.png)

A simple, full-stack application serving as a job portal. This project utilizes a **decoupled architecture** with a dedicated **React frontend** and a **Spring Boot RESTful backend**.

The application provides complete functionalities for **browsing, adding, updating, and deleting job offers (full CRUD)**, supported by a PostgreSQL database. The backend adheres strictly to the **Model-View-Controller (MVC)** pattern.

## 🌟 Key Features

* **Full CRUD Functionality:** Seamlessly **Create, Read, Update, and Delete** job offers.
* **Decoupled Architecture:** Separate codebase for frontend and backend, communicating via a **REST API**.
* **Database Persistence:** Reliable data storage using **PostgreSQL**.
* **Full Search and Browsing:** Functionality to search and browse all available job listings.

## 💻 Tech Stack & Architecture

The project is structured across two main branches, representing the decoupled architecture.

### Frontend (`react-front` branch)
The frontend is a single-page application (SPA) focused on providing a fast and dynamic user experience.

* **React**: Core library for building the user interface.
* **JavaScript/TypeScript**: Primary language for the client side.
* **HTML5 / CSS3 / Bootstrap**: Markup and styling.

### Backend (`java-backend` branch)
The backend acts as a **RESTful API service** responsible for business logic, data persistence, and enforcing security. This layer adheres to the MVC pattern.

* **Java 17+**: Core programming language.
* **Spring Framework 6**: Main application framework.
* **Spring Boot 3**: Used for auto-configuration and rapid development of the API.
* **Spring Data JPA**: Simplifies database interaction and implements the **Model** layer.
* **PostgreSQL**: Robust relational database used for data storage.

### Data & Communication
* **PostgreSQL**: Production-ready relational database.
* **REST API**: Communication protocol between the React frontend and the Spring backend.

## ⚙️ Development & Setup

### Prerequisites

Ensure you have the following installed:

* JDK 17 or newer.
* Apache Maven.
* Node.js and npm (for the React frontend).
* A running **PostgreSQL** instance.

### 1. Project Initialization

Clone the repository and navigate into the project directory:

```bash
git clone [https://github.com/Rafals/JobApp.git](https://github.com/Rafals/JobApp.git)
cd JobApp
