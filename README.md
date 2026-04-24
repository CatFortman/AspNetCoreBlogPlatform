# ASP.NET Core Blogging Platform

A simple blogging platform built with ASP.NET Core MVC and Entity Framework, allowing users to create, edit, view, and delete blog posts.

This project demonstrates full-stack web development concepts including MVC architecture, database integration, server-side rendering with Razor views, and logging.

## Features

- Create blog posts
- View all blog posts
- View blog post details
- Edit existing blog posts
- Delete blog posts
- Form validation
- Logging with Log4Net
- Responsive UI with Bootstrap

## Technologies Used

- ASP.NET Core 2.1
- C#
- Entity Framework / Entity Framework Core
- Razor Views
- Bootstrap 4
- Log4Net

## Project Structure

```text
BloggingSite/
│
├── Controllers/
│   ├── BlogPostsController.cs
│   └── HomeController.cs
│
├── Data/
│   └── BloggingContext.cs
│
├── Models/
│   ├── BlogPost.cs
│   ├── ErrorViewModel.cs
│   └── Topic.cs
│
├── Views/
│   └── BlogPosts/
│       ├── Index.cshtml
│       ├── Details.cshtml
│       ├── Create.cshtml
│       ├── Edit.cshtml
│       └── Delete.cshtml
│
├── wwwroot/
│
├── log4net.config
└── BloggingSite.csproj
```

## Architecture

This project follows the MVC (Model-View-Controller) design pattern:

- **Model**: Represents blog post data and database context.
- **View**: Razor pages used to render the UI.
- **Controller**: Handles user requests and business logic.

Example:

The `BlogPostsController` provides CRUD operations for managing blog posts asynchronously using Entity Framework.

## Example Workflow
- User navigates to `/BlogPosts/Create`
- User fills in blog title and content
- Form submits to the `Create` POST action
- Data is validated and saved to the database
- User is redirected to the blog post list

## Getting Started
### Prerequisites
- .NET Core SDK 2.1
- Visual Studio / Visual Studio Code
- SQL Server or LocalDB (depending on configuration)

## Installation

Clone the repository:

```
git clone https://github.com/CatFortman/AspNetCoreBlogPlatform.git
```

Navigate to the project directory:

```
cd your-repo-name
```

Restore dependencies:

```
dotnet restore
```

Apply migrations / update database:

```
dotnet ef database update
```

Run the application:

```
dotnet run
```

## Logging

This application uses Log4Net for logging and diagnostics.

Configuration is located in:

log4net.config

## Future Improvements
 - User authentication and authorization
 - Rich text editor for blog posts
 - Upgarde . NET
