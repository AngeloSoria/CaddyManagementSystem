# Caddy Management System

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Contact](#contact)

## Introduction

The **Caddy Management System** is a comprehensive solution designed to streamline the management of caddies in a golf course. This system helps in tracking caddy assignments, availability, and performance.

## Features

- **Caddy Registration**: Easily register new caddies with detailed information.
- **Assignment Management**: Assign caddies to golfers and manage their schedules.
- **Performance Tracking**: Monitor and evaluate caddy performance.
- **Availability Management**: Keep track of caddy availability and manage their shifts.
- **Reporting**: Generate detailed reports on caddy activities and performance.

## Installation

To install the Caddy Management System, follow these steps:

1. Download the repository as zip:
2. Extract it inside the `htdocs` of XAMPP.
3. Open the `CaddyManagementSystem/` project from htdocs.
4. Install the necessary dependencies (Must be inside the project folder when executing this via _cmd.exe_):
   ```bash
   composer install
   ```
5. Open XAMPP and start Apache and MySQL:
   - In the XAMPP Control panel, click the `Admin` button of MySQL (It will open the phpMyAdmin in the browser).
   - In the project file, local the sql file named `caddy_management_system.sql` inside the `config/` directory.
   - Import the sql file in the phpMyAdmin (it should import all the required info such as Database and Tables).

## Usage

1. Open your web browser and navigate to `http://localhost/CaddyManagementSystem`.
2. Register as an admin and log in.
3. Start managing caddies by adding new caddies, assigning them to golfers, and tracking their performance.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or suggestions, please contact us at [imangelosoria@gmail.com](mailto:imangelosoria@gmail.com).
