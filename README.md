# AirTicketSalesManagement

## Test Configuration
The test project reads settings from `AirTicketSalesManagementTests/appsettings.test.json`.
Update the `DefaultConnection` string in that file to match your local SQL Server instance.
=======

AirTicketSalesManagement is a desktop application built with Windows Presentation Foundation (WPF). It helps manage airline ticket sales, including booking flights and handling customer information.

## Prerequisites

- Windows operating system (required for WPF)
- .NET 8 SDK

## Build

```bash
dotnet build AirTicketSalesManagement.sln
```

## Test

```bash
dotnet test AirTicketSalesManagement.sln
```



