![AspNetCore-Runtime Code Sync](https://github.com/dotnet/aspnetcore/workflows/AspNetCore-Runtime%20Code%20Sync/badge.svg)

# Point Of Sales

This is an implementation of a minimal Point of Sales in Microsoft ASP.NET Core 3.1,
based on MVC architectural pattern using code first aproach with Entity Framework on
local machine using Microsoft SQL Database.

## Features

- [ASP.NET Core 3.1](http://www.dot.net/)
- [Entity Framework Core 3.1](https://docs.efproject.net/en/latest/)

## Pre-requisites

- [.Net core 3.1 SDK](https://www.microsoft.com/net/core#windows)
- [Microsoft SQL Server](https://www.microsoft.com/en-us/sql-server/sql-server-2017)
- [MVC Dashboard Identity](https://marketplace.visualstudio.com/items?itemName=CodeTuner.MvcDashboards)

## Installation

1. Clone the repo
```
    git clone https://github.com/saifciit/POS-ASP.NET-MVC
```
2. Change directory:
```
    cd beaverNet.POS
```
3. Restore packages:
```
    dotnet restore beaverNet.POS.sln
```
4. Run .Net project:
    F5 from either [Visual Studio IDE](https://www.visualstudio.com/) OR [VScode](https://code.visualstudio.com/):
    Note: If you are running using Visual Studio Code, install dev certificates using command:
    ```
    dotnet dev-certs https --trust
    ```
