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
