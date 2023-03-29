# Cretaceous Client

#### By E. Luckie ☀️

#### This is a follow-along project created using lessons on LearnHowToProgram.com on building an MVC application that communicates with a custom-built API. This application displays queryable data about a wildlife park consisting of creatures from the cretaceous period.

## Technologies Used

* C#
* .NET 7.0
* API
* NewtonSoft
* RestSharp
* Postman
* Markdown
* Git

### What is this? 

This is an example repo corresponding to multiple lessons within the LearnHowToProgram.com walkthrough on creating an ASP.NET Core MVC client to query a custom [ASP.NET Core API](https://github.com/epicodus-lessons/section-6-cretaceous-park-api-csharp-net6) in [Section 6: Building an API](https://www.learnhowtoprogram.com/c-and-net/building-an-api).

This project is called the "Cretaceous Client", while the API is called the "Cretaceous API".

This project was scaffolded using [`dotnet new`](https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-new).

## How To Run This Project

### Set Up and Run the Cretaceous Park API Project

First, follow the instructions in the README of [this repo](https://github.com/eluckie/CretaceousApi.Solution) to set up and run the Cretaceous Park API.

### Set Up and Run This Project

1. Clone this repo.
2. Open the terminal and navigate to this project's production directory called "CretaceousClient".
3. Within the production directory "CretaceousClient", run `dotnet watch run` in the command line to start the project in development mode with a watcher.
4. Open the browser to _https://localhost:7277/_. If you cannot access https://localhost:7277 it is likely because you have not configured a .NET developer security certificate for HTTPS. To learn about this, review this lesson: [Redirecting to HTTPS and Issuing a Security Certificate](https://www.learnhowtoprogram.com/lessons/redirecting-to-https-and-issuing-a-security-certificate).