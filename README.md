# Employee Management System

## Description

This Employee Management System is a command-line application built from scratch to manage a company's employee database. It uses Node.js, Inquirer, and PostgreSQL to allow business owners to view and manage departments, roles, and employees in their company, facilitating better organization and business planning.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Pictures](#apppictures)
- [Demo](#demo)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Installation

1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Run `npm install` to install the necessary dependencies.
4. Ensure you have PostgreSQL installed and running on your machine.
5. Create a database named `employees_db` in PostgreSQL.
6. Update the database connection details in the `app.js` file if necessary.
7. Run the schema and seed files to set up your database:
8. `psql -d employees_db -f db/schema.sql`
9. `psql -d employees_db -f db/seeds.sql`

## Usage

To start the application, run: `node index.js`

Follow the on-screen prompts to navigate through the application and manage your employee database.

## Features

- View all departments
- View all roles
- View all employees
- Add a department
- Add a role
- Add an employee
- Update an employee role

## App pictures
### Index
![indexTA](https://github.com/user-attachments/assets/8645d187-dcdf-4eef-a31d-6d2b43e93494)
### Departments
![departmentsTA](https://github.com/user-attachments/assets/6d0cc3bf-953b-4cc0-9fce-aa0ad49b639c)
### Employees
![employeesTA](https://github.com/user-attachments/assets/69255c35-8b88-44a6-b8c7-0c5a172d1c9d)



## Demo

[Link to Walkthrough Video](https://drive.google.com/file/d/1XiJroWNjv57noWfwg_vrYRKgSRf5IBBz/view?usp=sharing)

## Contributing

Contributions to improve the application are welcome. Please follow these steps:

1. Fork the repository
2. Create a new branch
3. Commit your changes 
4. Push to the branch 
5. Open a Pull Request

## License

This project did not required a license

## Contact

m.e.penafernandez@gmail.com