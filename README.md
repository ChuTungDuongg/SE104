# AirTicketSalesManagement

This repository contains a WPF application and a set of MSTest unit tests.

## Database configuration

`AirTicketDbContext` normally reads the database connection string from `appsettings.json`. If that file is missing, the context now falls back to an in-memory database so tests can run without a SQL Server instance. To use a real database, place `appsettings.json` next to `AirTicketSalesManagement.csproj` with a `DefaultConnection` entry.

## Running the tests

Ensure that the .NET SDK 8.0 or later is installed and then run:

```bash
cd AirTicketSalesManagementTests
dotnet test
```

The tests target `net8.0-windows`, so they require Windows or a compatible environment.
