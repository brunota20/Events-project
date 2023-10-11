# Events Project

This repository contains a web application for managing events using .NET Core 5 and Angular. The application provides a comprehensive introduction to various technologies and concepts, making it a valuable resource for developers looking to learn and practice their skills in building modern web applications. Below, you will find an overview of the project's features and a guide to getting started.

## Table of Contents

1. [Introduction](#introduction)
2. [Prerequisites](#prerequisites)
3. [Getting Started](#getting-started)
4. [Project Structure](#project-structure)
5. [Features](#features)
6. [Technologies Used](#technologies-used)
7. [Contributing](#contributing)
8. [License](#license)

## Introduction

This project was designed to learn and practice building web applications using the following technologies and concepts:

- .NET Core 5
- Entity Framework Core 5
- Angular
- Interpolation, Directives, and Binding in Angular
- Building .NET Core applications with multiple layers
- Organizing routes, displaying alerts, and more in Angular
- Building forms using Angular's Reactive Forms and creating a new layout
- Working with Data Transfer Objects (DTOs) and Data Annotations
- Registering events in Angular
- Integrating Angular with .NET for handling events and batches
- Uploading images
- Implementing authentication and authorization with ASP.NET Core Identity and JWT tokens
- Combining Angular, .NET Core Identity, and JWT for secure authentication
- Implementing pagination and filters
- Managing speakers and their social media profiles in the backend and frontend
- Integrating speakers, events, and other features in the year 2022

## Prerequisites

Before you begin, make sure you have the following software and tools installed on your system:

- [Node.js](https://nodejs.org/) - Required for Angular development.
- [.NET Core 5](https://dotnet.microsoft.com/download/dotnet/5.0) - Required for the backend development.

## Getting Started

To get started with this project, follow these steps:

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/your-username/events-project.git

2. Navigate to the project directory:

   ```bash
   cd events-project

3. Restore NuGet packages for the .NET Core backend:

   ```bash
   cd ..
    dotnet restore

4. Build and run the application:

   ```bash
   dotnet run


Open your web browser and access the application at http://localhost:5000.


# Project Structure

The project is structured as follows:

- **ClientApp:** Contains the Angular frontend application.
- **Controllers:** Contains the backend API controllers.
- **Data:** Includes database context and migrations.
- **DTOs:** Data Transfer Objects used for data validation and communication.
- **Entities:** Defines the application's data models.
- **Migrations:** Database migration files.
- **Services:** Business logic and services.
- **wwwroot:** Static web assets.
- **Startup.cs:** Configuration and startup logic.
- **Program.cs:** Application entry point.

# Features

Here are some of the key features of the Events Project:

- User authentication and authorization with JWT tokens.
- Event creation, management, and registration.
- Speaker profiles with social media links.
- Pagination and filtering of events.
- Image uploads for events and speakers.

# Technologies Used

The project leverages the following technologies and concepts:

- .NET Core 5
- Entity Framework Core 5
- Angular
- ASP.NET Core Identity
- JWT (JSON Web Tokens)
- Docker
- MySQL
- RESTful API design
- Reactive Forms in Angular
- Routing and navigation in Angular

# Contributing

Contributions to this project are welcome. If you'd like to contribute, please follow the standard GitHub Fork and Pull Request workflow. Be sure to review the project's Contributing Guidelines for more details.

# License

This project is licensed under the MIT License, which means you are free to use, modify, and distribute it for both personal and commercial purposes. Please review the license file for more details.

Happy coding!

