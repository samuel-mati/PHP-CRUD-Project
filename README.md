# PHP CRUD Project

This project is a simple PHP application demonstrating CRUD (Create, Read, Update, Delete) operations using a MySQL database. It provides basic functionality to manage users, doctors, and appointments within a hospital management system.

## Features

- User authentication: Login and logout functionality with password hashing for security.
- User management: CRUD operations to manage user accounts (admins, doctors, patients).
- Doctor management: Add, update, and delete doctor profiles with information such as name, specialty, and contact details.
- Appointment management: Schedule appointments with doctors, view existing appointments, and cancel appointments.

## Technologies Used

- PHP: Backend scripting language.
- MySQL: Relational database management system.
- HTML/CSS: Frontend markup and styling.
- Bootstrap: CSS framework for responsive design.
- Font Awesome: Icon library for user interface elements.
- XAMPP: Local development environment for running Apache, MySQL, and PHP.

## Setup Instructions

1. Clone the repository to your local machine:

_git clone https://github.com/your-username/php-crud-project.git_


2. Import the `database.sql` file into your MySQL database to create the necessary tables and sample data.

3. Configure the database connection in the `con.php` file with your MySQL credentials.

4. Start your local server (e.g., using XAMPP) and navigate to the project directory in your web browser.

5. You should be redirected to the login page. Use the default admin credentials (username: admin, password: admin) to log in and start using the application.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please fork the repository, make your changes, and submit a pull request. For major changes, please open an issue first to discuss the proposed changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
