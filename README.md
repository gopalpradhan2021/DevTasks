# DevTasks

A Clean Architecture .NET Core + React project for learning modular, maintainable, and scalable enterprise application development.

## 🧱 Layers
- **DevTasks.Domain** – Core business logic and entities  
- **DevTasks.Application** – Application services and interfaces  
- **DevTasks.Infrastructure** – Database, EF Core, and external services  
- **DevTasks.Api** – Web API layer (controllers, endpoints)

## 🚀 Tech Stack
- .NET 8 / .NET Core
- C# 10+
- Entity Framework Core
- React + TypeScript
- SQL Server / PostgreSQL
- Docker + AWS / Azure support

## ⚙️ How to Run
```bash
dotnet build
dotnet run --project src/DevTasks.Api
