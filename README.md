# Warehouse Printing App

A web application designed to manage and print location labels for warehouses, including main and buffer locations, with support for DataMatrix codes.

## Features
- Upload CSV files with location data.
- Print individual labels or batch labels for halls and warehouses.
- Group main and buffer locations for easy navigation.
- Role-based access for admins and users.

## Prerequisites
- [.NET 8 SDK](https://dotnet.microsoft.com/download)
- SQL database (SQLite used in development)

## Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/warehouse-printing-app.git
   ```
2. Navigate to the project folder:
   ```bash
   cd warehouse-printing-app
   ```
3. Restore dependencies:
   ```bash
   dotnet restore
   ```
4. Apply migrations to set up the database:
   ```bash
   dotnet ef database update
   ```
5. Run the application:
   ```bash
   dotnet run
   ```

## Usage
- Navigate to `http://localhost:5000` (or the specified port) in your browser.
- Log in with your user credentials to access features.

