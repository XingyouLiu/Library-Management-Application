# Library Management System

## Overview

This full-stack Library Management System provides a comprehensive platform for managing library resources. It offers features for both users and administrators, enabling efficient book management, borrowing operations, and user interactions.

## Key Features

- User authentication and role-based access control (USER/ADMIN)
- Real-time CRUD operations for books and comments
- User-friendly interface for browsing, borrowing, rating and reviewing books
- Admin dashboard for book management and user inquiry handling
- Secure payment processing for overdue fees
- Image upload and pagination for enhanced user experience

## Installation

### Prerequisites

- Java
- Node.js and npm
- MySQL
- Maven

### Setup

1. Clone the repository
2. Backend setup:
   ```
   cd backend/spring-boot-library
   mvn install
   mvn spring-boot:run
   ```
3. Frontend setup:
   ```
   cd frontend/react-library
   npm install
   npm start
   ```

## Usage

- Access the application at `http://localhost:3000`
- Use the interface to browse books, manage your account, and perform library operations
- Admins can access the dashboard for comprehensive management features

## Security

The application implements robust security measures, including JWT, OAuth2, and OpenID Connect for authentication and authorization.
