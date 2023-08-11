# ContosoPizza-
ASP.NET Core Web API

# ContosoPizza - RESTfull API with ASP.NET Core Controllers

A simple RESTFul service with ASP.NET Core Controllers that support create, read, update and delete. (CRUD) operations.



## Table of Contents
- [Technologies Used](#technologies-used)
- [Features](#features)
- [Setup](#setup)
- [Room for Improvement](#room-for-improvement)
- [Acknowledgements](#acknowledgements)

## Technologies Used
- C#
- ASP.NET Core
- .NET CLI
- Visual Studio Code


## Features

- GET: Retrieve data from the web service.
- POST: Create a new item of data on the web service.
- PUT: Update an item of data on the web service.
- DELETE: Delete an item of data on the web service.


## Setup

- Clone Repository

- .NET 6.0 SDK required:

In the CLI write 

```dotnet --list-sdks```

If you don't get the following output:

```
3.1.100 [C:\program files\dotnet\sdk]
5.0.100 [C:\program files\dotnet\sdk]
6.0.100 [C:\program files\dotnet\sdk]
```
Please install the <a href="https://dotnet.microsoft.com/en-us/download">6.0 SDK</a>

In the terminal (CLI) write

```dotnet run```

- Open a new intergrated terminal

For a trusted certificate to be created please run 

```dotnet dev-certs https --trust```

Then to connect to the Web API please run 

```connect https://localhost:{PORT}```

Go to the 'Pizza' endpoint by the following command:

```cd Pizza```

Then..

```ls```

The following should be the output of the previous command:

```
https://localhost:{PORT}/Pizza> ls
    .      [GET|POST]
    ..     []
    {id}   [GET|PUT|DELETE]
```

You can now see a list of possible commands. As for example:

```post -c "{"name":"Hawaii", "isGlutenFree":false}"```

To create a new Data entry.

## Room for Improvement

Create a ASP.NET appliction that uses the WEB API.

## Acknowledgements

- Tuturial through Microsoft.Learn