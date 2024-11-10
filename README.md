# SkyLand Store

SkyLand Store is a modern, feature-rich e-commerce platform built using a robust and scalable architecture. The project emphasizes clean code, secure authentication, and efficient data handling to provide a seamless shopping experience.

---

## Features

- **AutoMapper & DTO**: Efficiently map and transform data between layers using Data Transfer Objects (DTOs) and AutoMapper.
- **4-Tier Architecture**:
  1. **Database Layer**: Manages data persistence.
  2. **Business Logic Layer**: Contains core business rules and logic.
  3. **Service Layer**: Facilitates interaction between controllers and business logic.
  4. **Presentation Layer**: Handles application startup and user-facing interactions.
- **Redis Caching**: Boosts performance and reduces database load using in-memory caching.
- **Design Patterns**:
  - **Generic Repository Pattern**: Provides a flexible and reusable data access layer.
  - **Specification Pattern**: Encapsulates complex query logic for reusable and testable code.
  - **Pagination Pattern**: Efficiently handle large datasets by dividing data into manageable pages.
- **JWT Authentication**: Ensures secure access with JSON Web Token (JWT) based authentication.
- **Data Seeding**: Populates the database with initial data for testing or production.
- **Error & Exception Handling**:
  - Centralized error handling with **Exception Middleware**.
  - Consistent and meaningful API error responses.
- **Multi-Database Support**:
  - **Product Database**: Stores product-related information.
  - **Customer Database**: Manages customer profiles and transactions.

---
## Installation

### Prerequisites
- .NET 6 or later
- SQL Server
- Redis
- Visual Studio / VS Code
