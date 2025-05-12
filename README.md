# Online Art Gallery

A full-stack web application for showcasing and managing art pieces, built with React.js and Spring Boot.

## Features

- Browse art gallery with images, titles, and artist information
- Search and filter functionality
- Detailed view for each art piece
- Responsive design for desktop and mobile
- User authentication and authorization
- Admin panel for managing art pieces
- RESTful API backend

## Tech Stack

### Frontend
- React.js
- Material-UI for components
- React Router for navigation
- Axios for API calls

### Backend
- Spring Boot
- Spring Security
- Spring Data JPA
- MySQL Database
- JWT Authentication

## Project Structure

```
artgallery/
├── frontend/           # React.js frontend application
└── backend/           # Spring Boot backend application
```

## Getting Started

### Prerequisites
- Node.js (v14 or higher)
- Java 17 or higher
- MySQL 8.0 or higher
- Maven

### Backend Setup
1. Navigate to the backend directory
2. Configure database connection in `application.properties`
3. Run `mvn spring-boot:run`

### Frontend Setup
1. Navigate to the frontend directory
2. Run `npm install`
3. Run `npm start`

## API Documentation

The API documentation will be available at `http://localhost:8080/swagger-ui.html` when the backend is running.

## License

MIT 