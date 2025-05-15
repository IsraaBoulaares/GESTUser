# GESTUser 👤

**GESTUser** is a user management microservice built using **Spring Boot**, designed to handle user-related operations in a scalable and modular way. It can be integrated into a larger microservices architecture and secured using Keycloak or Spring Security.

## 🚀 Features

- 🔐 User authentication and role-based authorization (extensible with Keycloak)
- 🧩 RESTful API for user management (CRUD)
- ⚙️ Microservice-friendly structure
- 🧠 Clean architecture using service and repository layers
- 🛡️ Security-ready with support for OAuth2

## 🛠️ Tech Stack

| Technology         | Description                            |
|--------------------|----------------------------------------|
| Java 17            | Programming language                   |
| Spring Boot        | Backend framework                      |
| Spring Data JPA    | ORM and database access                |
| Lombok             | Reduces boilerplate code               |
| H2 / MySQL         | In-memory or persistent database       |
| Spring Security    | Security and authentication (optional) |

## 📂 Project Structure

GESTUser/
├── controller/ # REST controllers
├── entity/ # User entity models
├── repository/ # JPA repositories
├── service/ # Business logic services
├── config/ # Configuration files
└── GESTUserApplication.java

bash
Copy
Edit

## ▶️ Getting Started

### Prerequisites

- Java 17+
- Maven installed

### Run the Application

```bash
# Clone the repository
git clone https://github.com/IsraaBoulaares/GESTUser.git
cd GESTUser

# Build and run
./mvnw spring-boot:run
The application will start on http://localhost:8080.

📡 API Endpoints
Method	Endpoint	Description
GET	/users	Get all users
GET	/users/{id}	Get user by ID
POST	/users	Create a new user
PUT	/users/{id}	Update user by ID
DELETE	/users/{id}	Delete user by ID
