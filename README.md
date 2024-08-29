# Gym Management System

![Gym Management System](https://img.shields.io/badge/Status-Active-brightgreen.svg)

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction
The **Gym Management System** is a comprehensive application designed to help gym owners and staff manage their gym operations efficiently. The system provides tools for managing members, handling memberships, tracking attendance, and scheduling classes. It aims to streamline the management of gym activities, reducing the workload of administrative staff.

## Features
- **Member Management:** Add, update, and delete member profiles.
- **Membership Management:** Manage different membership plans and their validity periods.
- **Attendance Tracking:** Track member attendance using an easy-to-use interface.
- **Class Scheduling:** Schedule gym classes and manage bookings.
- **Payment Management:** Record and track member payments and dues.
- **Reports:** Generate reports on member attendance, payments, and membership statistics.
- **User Authentication:** Secure login for staff and admin.

## Technologies Used
- **Frontend:** HTML, CSS, JavaScript
- **Backend:** PHP, MySQL
- **Database:** MySQL
- **Libraries:** Bootstrap, jQuery

## Installation

### Prerequisites
- XAMPP/WAMP/MAMP or any other web server with PHP and MySQL support.
- A web browser (Google Chrome, Firefox, etc.).

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/Farhan-AP/Gym-Management-System-.git
   ```
2. Move the project folder to the `htdocs` directory of your XAMPP or WAMP installation.
3. Import the database:
   - Open `phpMyAdmin`.
   - Create a new database (e.g., `gym_management`).
   - Import the SQL file located in the `database` folder into the newly created database.
4. Configure the database connection:
   - Open the `config.php` file in the project.
   - Set the database name, username, and password according to your setup.
5. Start the web server and navigate to `http://localhost/Gym-Management-System-` to access the application.

## Usage
1. **Admin Login:**
   - Use the default admin credentials provided or create a new admin user from the database.
2. **Managing Members:**
   - Navigate to the `Members` section to add, edit, or remove member information.
3. **Membership Plans:**
   - In the `Membership` section, create and manage different membership plans.
4. **Tracking Attendance:**
   - Use the `Attendance` feature to mark and review member attendance.
5. **Payments and Reports:**
   - Track payments and generate reports through the `Payments` and `Reports` sections.

## Screenshots
Add screenshots here to visually represent the application.

## Contributing
Contributions are welcome! If you'd like to contribute, please fork the repository and submit a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact
For any inquiries or issues, please contact [Farhan AP](mailto:your-email@example.com).
