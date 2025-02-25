# Movie Database App

This project is a Movie Database Application built using Blazor Server. It follows the tutorial provided by Microsoft: [Create a database app with Blazor](https://learn.microsoft.com/en-us/aspnet/core/blazor/tutorials/movie-database-app/part-3?view=aspnetcore-9.0&pivots=vsc).

## Features

- Create, read, update, and delete movie entries.
- Search for movies by title.
- Responsive design for various screen sizes.

## Prerequisites

- [.NET 6.0 SDK](https://dotnet.microsoft.com/download/dotnet/6.0)
- [Visual Studio Code](https://code.visualstudio.com/)
- [SQL Server](https://www.microsoft.com/en-us/sql-server/sql-server-downloads)

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/MovieDatabaseApp.git
   cd MovieDatabaseApp/BlazorWebAppMovies
   ```

2. Restore the dependencies:

   ```bash
   dotnet restore
   ```

3. Update the database connection string in `appsettings.json`.

4. Apply the database migrations:

   ```bash
   dotnet ef database update
   ```

5. Run the application:

   ```bash
   dotnet run
   ```

6. Open your browser and navigate to `https://localhost:5001`.

## Project Structure

- `BlazorWebAppMovies` - The Blazor WebAssembly project.
- `BlazorWebAppMovies.Server` - The ASP.NET Core Web API project.
- `BlazorWebAppMovies.Shared` - Shared models and services.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [Microsoft Learn](https://learn.microsoft.com/en-us/aspnet/core/blazor/tutorials/movie-database-app/part-3?view=aspnetcore-9.0&pivots=vsc) for the tutorial and guidance.
