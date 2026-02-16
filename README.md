# BookMyStay

BookMyStay is a Full Stack Hotel and Resort Booking Application built using Spring Boot and ReactJS.  
The system implements secure JWT-based authentication, role-based access (Customer/Owner), and a layered backend architecture with RESTful APIs.

---

## Tech Stack

Backend:
- Java
- Spring Boot
- Spring Security
- JWT Authentication
- JPA / Hibernate
- MySQL

Frontend:
- ReactJS (Vite)
- JavaScript
- Axios
- Formik Validation
- Responsive UI

---

## Key Features

- Secure User Signup and Login (JWT Authentication)
- Role-Based Access Control (Customer / Owner)
- Add, Update, Delete Resorts (Owner)
- View Resorts and Details (Customer)
- Booking Management with Status Tracking
- Review and Rating System
- Global Exception Handling
- Structured REST API Architecture

---

## Architecture

The backend follows a clean layered structure:

Controller → Service → Repository → Database

- Controllers manage REST endpoints
- Service layer handles business logic
- Repository layer interacts with MySQL
- JWT filter secures protected routes
- Global exception handler provides structured error responses

---

## Project Structure

backend/  - Spring Boot REST API  
frontend/ - React Application  

---

## Sample API Endpoints

Authentication:
- POST /api/auth/signup
- POST /api/auth/login

Resorts:
- GET /api/resorts
- POST /api/resorts
- PUT /api/resorts/{id}
- DELETE /api/resorts/{id}

Bookings:
- POST /api/bookings
- GET /api/bookings/user
- GET /api/bookings/owner

Reviews:
- POST /api/reviews
- GET /api/reviews/{resortId}

---

## How to Run

Backend:
1. Configure MySQL in application.properties
2. Run: mvn spring-boot:run

Frontend:
1. Navigate to frontend folder
2. Run: npm install
3. Run: npm run dev

---

## Future Improvements

- Payment Gateway Integration
- Admin Dashboard
- Pagination and Advanced Filtering
- Cloud Deployment
- Docker Containerization

---

Author: Gowtham D  
Full Stack Developer (Java + React)
