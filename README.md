# Chess Platform

A comprehensive chess platform built with ASP.NET Core, providing a robust API for chess-related functionalities including user management, game handling, and more.

## Architecture

This project follows Clean Architecture principles with the following layers:

- **Chess.Domain**: Contains domain entities, value objects, and business rules.
- **Chess.Application**: Contains application services, DTOs, and use cases.
- **Chess.Infrastructure**: Contains data access, external services, and infrastructure concerns.
- **Chess.API**: The REST API layer exposing endpoints via ASP.NET Core.

## Technologies Used

- **Framework**: ASP.NET Core 8.0
- **Database**: PostgreSQL with Entity Framework Core
- **Authentication**: JWT Bearer Tokens with ASP.NET Core Identity
- **API Documentation**: Swagger/OpenAPI
- **Architecture**: Clean Architecture

## Prerequisites

- .NET 8.0 SDK
- PostgreSQL database
- Visual Studio 2022 or VS Code with C# extensions

## API Endpoints

The API provides endpoints for:
- User registration and authentication
- Chess game management
- Player profiles
- Game history