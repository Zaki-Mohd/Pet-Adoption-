# Pet Adoption Project

## Description
This project is a **Pet Adoption Web Application** that allows users to view pets available for adoption, register, log in, and adopt a pet. It includes a **frontend** interface built with **HTML**, **CSS**, and **JavaScript** along with a **backend** powered by **Express.js** and **EJS** templates. The project also connects to a **MySQL** database to manage user authentication and pet adoption records.

---

## Features

- **Homepage**: Displays the pets available for adoption.
- **Login/Registration**: Allows users to log in or register.
- **Adoption**: Users can adopt a pet after logging in.
- **Admin Panel**: Admins can manage pet records.
- **User Authentication**: Only logged-in users can adopt pets.

---

## Installation

### Prerequisites

Ensure you have the following installed:

- **Node.js**: [Install Node.js](https://nodejs.org/)
- **MySQL**: [Install MySQL](https://dev.mysql.com/downloads/)
- **Git** (optional, but recommended for version control): [Install Git](https://git-scm.com/downloads)

### Setup

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/pet.git
2. Navigate to the project folder:
   cd pet
3. Install the required dependencies:
   npm install
4. Set up the database by importing the schema from schema.sql into your MySQL database.

5. Configure your .env file with your MySQL database credentials:
  -> DB_HOST: Your MySQL database host (usually localhost)
  -> DB_USER: Your MySQL username
  -> DB_PASSWORD: Your MySQL password
  -> DB_NAME: Your database name.

6. Run the project:
    npm start

7. Open your browser and go to http://localhost:3000 to view the application.

## Database Schema
The project uses the following tables:

Users: Stores user login credentials.
Pets: Stores pet details (e.g., name, breed, age).
AdoptionRecords: Tracks which user adopted which pet.

## Usage
 Homepage: Displays available pets for adoption.
 Login: Users can log in with their credentials.
 Register: New users can create an account.
 Adopt: After logging in, users can adopt a pet by clicking on the "Adopt" button.
 Admin: Admins can log in to manage pet records (add/remove pets).

## Technologies Used
Frontend: HTML, CSS, JavaScript
Backend: Node.js, Express.js, EJS
Database: MySQL
Authentication: MySQL-based user authentication

## Contributing
If you want to contribute to the project, follow these steps:

Fork the repository.
Clone your fork to your local machine.
Create a new branch for your changes.
Make your changes and commit them.
Push your changes to your fork.
Create a pull request to the main repository.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
