# KrishiKart - Backend

This is the backend/API of the KrishiKart Agriculture Equipment Rental System.

## Technologies Used

- ASP.NET Core Web API
- C#
- Entity Framework Core
- SQL Server
- JWT Authentication
- Razorpay Payment Integration
- Swagger

## Features

- User Registration and Login
- JWT-based Authentication
- Farmer Management
- Machinery Management
- Owner Management
- Booking Management
- Maintenance Management
- Invoice Management
- Payment Management
- Razorpay Payment Integration
- RESTful APIs
- Entity Framework Core for database operations

## Project Structure

- `Controllers` - API controllers
- `Models` - Database entity models
- `Dto` - Data Transfer Objects
- `Services` - Business logic
- `Data` - Database context and SQL scripts
- `Program.cs` - Application configuration

## Database

The application uses **Microsoft SQL Server** as the database and **Entity Framework Core** for database access.

## How to Run

1. Open the project in Visual Studio.
2. Configure the SQL Server connection string in `appsettings.json`.
3. Configure JWT settings.
4. Restore NuGet packages.
5. Build and run the application.
6. Use Swagger to test the APIs.
