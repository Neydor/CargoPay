# CargoPay

## Requirements

To run this project, you will need:

- .NET 8 SDK
- SQL Server (or any other supported database)

## Database Scripts

The database scripts are located in the `CargoPay.Infrastructure/Migrations/DATABASE_SCRIPTS.sql` folder. You can find the necessary SQL files to create and populate the database.

## Configuring the Database Connection

To modify the database connection string, follow these steps:

1. Open the `appsettings.json` file located in the root of the project.
2. Locate the `ConnectionStrings` section.
3. Update the `DefaultConnection` attribute with your database details. For example:


## Running the Project

1. Ensure you have the .NET 8 SDK installed.
2. Ensure your database is running and accessible.
3. Open the solution in Visual Studio 2022.
4. Set CargoPay.API as Startup project.
5. It's better the local execution in IIS Express, in Docker work, to, but the ports could be block by firewall.
6. Build the solution to restore all dependencies.
7. Run the project using Visual Studio or the .NET CLI.
