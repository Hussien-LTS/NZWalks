# ASP.NET Core Web API with .NET 8, Entity Framework Core, and SQL Server

This project is a result of completing the **"ASP.NET Core Web API with .NET 8, Entity Framework Core, and SQL Server"** course on Udemy. The course provided a comprehensive guide to building RESTful APIs using the latest .NET technologies, including .NET 8, Entity Framework Core (EF Core), and SQL Server.

---

## Course Overview

This course is designed for developers of all skill levels, particularly beginners and intermediate developers familiar with C# and ASP.NET Web MVC. It focuses on creating a robust and scalable ASP.NET Core Web API while adhering to REST principles and best practices.

### Key Topics Covered

- **REST API Principles**: Understanding and implementing RESTful APIs.
- **ASP.NET Core Web API**: Building APIs using .NET 8 and C#.
- **Entity Framework Core (EF Core)**: Database management and migrations.
- **SQL Server**: Creating and managing databases.
- **Repository Pattern**: Implementing clean architecture for CRUD operations.
- **Automapper**: Mapping domain models to DTOs.
- **Asynchronous Programming**: Using `async` and `await` for efficient API performance.
- **Validation**: Ensuring data integrity in API requests.
- **Authentication & Authorization**: Securing APIs using JWT tokens and ASP.NET Core Identity.
- **Advanced Features**: Implementing filtering, sorting, and pagination.
- **Testing**: Using Swagger UI and Postman for API testing.

---

## Project Description

The project involves creating a **Web API for managing regions and walks of New Zealand**. The API allows clients to consume data about regions and walks, perform CRUD operations, and implement advanced features like filtering, sorting, and pagination.

### Features

1. **RESTful Endpoints**: Create, Read, Update, and Delete (CRUD) operations for regions and walks.
2. **Database Integration**: Use Entity Framework Core and SQL Server for data storage.
3. **Authentication & Authorization**: Secure the API using JWT tokens and role-based access control.
4. **Advanced Functionality**: Implement filtering, sorting, and pagination for efficient data retrieval.
5. **Testing**: Test API endpoints using Swagger UI and Postman.

---

## Technologies Used

- **.NET 8**: Latest version of the .NET framework.
- **ASP.NET Core**: For building the Web API.
- **Entity Framework Core (EF Core)**: For database management and migrations.
- **SQL Server**: As the relational database.
- **Automapper**: For object-to-object mapping.
- **JWT Tokens**: For authentication and authorization.
- **Swagger UI**: For API documentation and testing.
- **Postman**: For API endpoint testing.

---

## What I Learned

- Designed and implemented a RESTful Web API using ASP.NET Core and .NET 8.
- Used Entity Framework Core and SQL Server for database management.
- Applied the Repository Pattern for clean and maintainable code.
- Implemented authentication and authorization using JWT tokens and ASP.NET Core Identity.
- Added advanced features like filtering, sorting, and pagination to enhance API functionality.
- Tested APIs using Swagger UI and Postman.

---

## How to Run the Project

1. **Clone the Repository**:

   ```bash
   git clone git@github.com:Hussien-LTS/NZWalks.git  
   ```

2. **Set Up the Database**:

   - Update the connection string in appsettings.json.

   - Run EF Core migrations to create the database:

   ```bash
    dotnet ef database update
   ```

3. **Run the Application**:

   ```bash
    dotnet run
   ```

4. **Test the API**:

    - Use Swagger UI by navigating to /swagger in your browser.

    - Alternatively, use Postman to test the endpoints.

## Course Completion Certificate

[![Udemy Certificate](https://img.shields.io/badge/Udemy-Certificate-brightgreen)](https://www.udemy.com/certificate/UC-8974f60d-1344-4200-b1de-6c572a22dd39/)

## Connect with Me

- LinkedIn: [LinkedIn Profile](https://www.linkedin.com/in/hussein-almohamd/)
- GitHub: [GitHub Profile](https://github.com/Hussien-LTS/)

**Thank you for checking out my project!** 🚀
