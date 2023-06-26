# First API with ASP.NET CORE Controllers
This is the fourth and last project of the official **Build .NET applications with C#** course in the Microsoft Learn platform.

## Objectives
- Perform basic CRUD operations for the Pizza Model.
- Using an in-memory cached model (just a static class service to persist data while the app runs).
- Test the CRUD endpoints with the httprepl command-line tool. 

## dotnet related used commands

    dotnet new webapi -f net6.0
    dotnet run
    dotnet tool install -g Microsoft.dotnet-httprepl
    httprepl https://localhost:7144
    dotnet dev-certs https --trust
    dotnet build
    dotnet run
    dotnet new gitignore

## httprepl related used commands

    ls
    cd pizza
    get
    get 1
    post "{}"
    put 1 "{}"
    delete 3
    connect https://localhost:port

