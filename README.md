# JokesWebApp

JokesWebApp is a web application developed with ASP.NET Core (MVC) that allows users to read, share, and manage jokes. The app includes authentication and authorization, enabling users to securely log in and manage their accounts. With full CRUD operations and search functionality, JokesWebApp provides a user-friendly platform to interact with a vast collection of jokes.

## Features

- **Authentication and Authorization:** Secure user registration, login, and role-based access control.
- **CRUD Operations:** Create, Read, Update, and Delete jokes with an intuitive interface.
- **Search Functionality:** Easily find jokes by keywords or categories.
- **Responsive Design:** Accessible on various devices with a user-friendly interface.

## Technologies Used

- ASP.NET Core (MVC)
- Entity Framework Core
- SQL Server
- Bootstrap for styling

## Getting Started

### Prerequisites

- [.NET SDK](https://dotnet.microsoft.com/download)
- [SQL Server](https://www.microsoft.com/en-us/sql-server/sql-server-downloads)
- [Node.js](https://nodejs.org/) (for front-end development)

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/JokesWebApp.git
    ```

2. Navigate to the project directory:
    ```bash
    cd JokesWebApp
    ```

3. Restore dependencies:
    ```bash
    dotnet restore
    ```

4. Update the database connection string in `appsettings.json`:
    ```json
    "ConnectionStrings": {
        "DefaultConnection": "Server=(localdb)\\mssqllocaldb;Database=JokesWebAppDb;Trusted_Connection=True;MultipleActiveResultSets=true"
    }
    ```

5. Apply database migrations:
    ```bash
    dotnet ef database update
    ```

6. Run the application:
    ```bash
    dotnet run
    ```

### Usage

1. Register a new account or log in with an existing account.
2. Browse the home page to view the latest jokes.
3. Use the navigation menu to add new jokes, edit or delete existing ones, and search for jokes.
4. Manage your account settings from the profile page.

### Contributing

We welcome contributions! Follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -am 'Add a new feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a pull request.

### License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

### Contact

For any questions or feedback, please contact us at support@jokeswebapp.com.

---

Enjoy using JokesWebApp and spread the laughter!
