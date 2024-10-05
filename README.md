# Shipping Management System

The **Shipping Management System** is a robust platform developed using **C#**, **.NET**, and **Microsoft SQL Server**. It enables customers to purchase products, employees to manage orders, and admins to oversee all operations. This system is designed to optimize the shipping and order management process for businesses, providing seamless user interaction across all roles.

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [User Roles and Functionalities](#user-roles-and-functionalities)
  - [Customer](#customer)
  - [Employee](#employee)
  - [Admin](#admin)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

---

## Features

- **Product Purchase**: Customers can browse and purchase products from an available catalog.
- **Order Management**: Employees can view, manage, and cancel orders.
- **User Management**: Admins have full control over user accounts and their privileges.
- **Password Management**: Users can update their account passwords for security.
- **Order History**: Customers can view their past orders and track statuses.
- **Cancellation Management**: Both customers and employees can cancel orders under specified conditions.
- **Profile Management**: Employees can update their personal details and view their profiles.

---

## Technologies Used

- **C#** - Backend logic and core functionality.
- **.NET Framework** - Application framework for developing web and backend services.
- **ASP.NET MVC** - Web application framework used to implement the Model-View-Controller pattern.
- **Microsoft SQL Server** - Relational database management system for data storage and querying.
- **Entity Framework** - ORM (Object-Relational Mapping) for data access between the application and the database.

---

## User Roles and Functionalities

### Customer
Customers have access to the following features:
- **Product Browsing and Search**: Search for products and view detailed information.
- **Order Placement**: Add items to a cart and complete the checkout process.
- **Password Management**: Update account passwords for security.
- **Order History**: Review previous orders and track their statuses.
- **Order Cancellation**: Cancel orders that have not been processed.

### Employee
Employees are responsible for managing customer orders and have the following capabilities:
- **View and Manage Orders**: Access a list of orders and update their statuses.
- **Cancel Orders**: Process cancellations requested by customers.
- **Profile Management**: View and update personal information.
- **Password Management**: Change account password for enhanced security.

### Admin
Admins have comprehensive control over the system and its users. Admins can:
- **Manage Products**: Add, edit, or remove products from the catalog.
- **Manage Users**: View and modify customer and employee accounts.
- **Oversee Orders**: Access and manage all orders placed in the system.
- **System Configuration**: Configure application settings and manage data integrity.

---

## Installation

To install and run the **Shipping Management System** locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/ArifurRahmanShezan/Shipping-Management-System.git
   ```

2. Open the project in **Visual Studio**.

3. Restore the necessary NuGet packages:
   ```bash
   dotnet restore
   ```

4. Update the database connection string in `appsettings.json` (for .NET Core) or `Web.config` (for .NET Framework) to point to your SQL Server instance.

5. Apply migrations to set up the database:
   ```bash
   dotnet ef database update
   ```

6. Build and run the project:
   ```bash
   dotnet run
   ```

---

## Usage

Once the application is up and running:

- **Customers** can register, log in, and browse products. They can place orders, view their order history, and manage their accounts.
- **Employees** can log in to view and manage orders, assist customers with cancellations, and update their profiles.
- **Admins** can log in to manage all aspects of the system, including products, users, and orders.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

---

## Contact Information

For any queries or issues regarding the project, please reach out to:

- **Developer**: Arifur Rahman Shezan
- **Email**: [arifurrahmanshezan@gmail.com](mailto:arifurrahmanshezan@gmail.com) 
