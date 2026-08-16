# University Portal - ASP.NET Core MVC + ADO.NET

Project type: ASP.NET Core MVC Web Application (.NET 8)

## Structure
- `UniversityPortal.sln` - Visual Studio solution
- `src/UniversityPortal.csproj` - ASP.NET Core MVC project
- `src/Controllers` - MVC controllers
- `src/Models` - entity/view models
- `src/Data` - ADO.NET connection factory and repositories
- `src/Views` - Razor MVC views
- `src/wwwroot` - CSS and JavaScript
- `src/Database` - SQL Server database script and stored procedures
- `src/Properties/launchSettings.json` - Visual Studio run profiles

## Run
1. Open `UniversityPortal.sln` in Visual Studio 2022.
2. Run `src/Database/01_CreateDatabase.sql` in SQL Server.
3. Update `src/appsettings.json` with your SQL Server connection string.
4. Build and run the `UniversityPortal` project.
