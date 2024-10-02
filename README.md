# E-Library Management System

This is an **E-Library Management System** built using **ASP.NET** and **ADO.NET** with C#. It includes both an admin panel for managing authors, books, and users, and a user panel for browsing, viewing, and borrowing books. The system simplifies library operations, offering a streamlined interface for both administrators and users.

## Features

### Admin Panel:
- Add, update, and delete books and authors.
- Manage user accounts (activate, deactivate, and view status).
- View user borrowing activity and manage user statuses.

### User Panel:
- View available books.
- Borrow books and manage book returns.
- View personal borrowing history.

## How to Run

To run this project, follow the steps below:

### Prerequisites
1. **Visual Studio** with the following workloads installed:
   - ASP.NET and web development.
   - C# development.
   
2. **SQL Server Management Studio (SSMS)** for managing the database.

### Steps

1. **Clone the repository or download zip** and open it in Visual Studio.
2. **Install required NuGet packages** by restoring the project in Visual Studio.
3. **Set up the database**:
   - Use SSMS to create a new database for the e-library.
   - Execute the provided SQL script to create tables and initial data.
   - Update the connection string in `appsettings.json` with your SQL Server credentials.
   
4. **Build the project** in Visual Studio.
5. **Run the application** to access the admin panel and user interface:
   - Admins can log in to manage books, authors, and users.
   - Users can view available books and borrow them.
   - Make sure **Vp Assinmnt 3** folder and **Vp Assinmnt 3.sln** is in same folder.
6. **Note** User Panel is not complete but all css template & html code is in **E-Library** folder.

