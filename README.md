# PG Life

## Description
PG Life is a web application designed to help users find and manage paying guest accommodations. This project is built using PHP and aims to provide a seamless user experience with features like search, filtering, and user authentication.

## Features
- User Registration and Authentication
- Search for PGs by City
- Filter PGs by Rent and Rating
- Mark PGs as Interested
- View Detailed PG Information
- User Dashboard to Manage Interested PGs
- Responsive Design

## Technologies Used
- PHP
- MySQL
- HTML
- CSS
- JavaScript
- jQuery
- Bootstrap

## Installation

### Prerequisites
- PHP 7.4 or higher
- MySQL 5.7 or higher
- Apache or Nginx server

### Steps
1. **Clone the repository**
    ```bash
    git clone https://github.com/yourusername/pglife.git
    cd pglife
    ```

2. **Set up the database**
    - Create a MySQL database.
    - Import the provided SQL file to set up the database schema.
    ```sql
    CREATE DATABASE pglife;
    USE pglife;
    SOURCE path/to/your/sql/file.sql;
    ```

3. **Configure the application**
    - Rename `config.example.php` to `config.php`.
    - Update the database configuration in `config.php`.
    ```php
    define('DB_HOST', 'localhost');
    define('DB_USER', 'your_db_user');
    define('DB_PASS', 'your_db_password');
    define('DB_NAME', 'pglife');
    ```

4. **Start the server**
    - If using Apache, place the project in the `htdocs` directory.
    - If using Nginx, configure the server block to point to the project directory.
    - Start the server and navigate to `http://localhost/pglife` in your web browser.

## Usage
- **Home Page**: Search for PGs by entering a city name.
- **PG List Page**: View and filter PG listings by rent and rating.
- **PG Details Page**: View detailed information about a selected PG.
- **User Dashboard**: Manage your interested PGs and view account details.

## Screenshots
!Home Page
!PG List Page

## Contributing
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Contact
- **Your Name** - dm-mishra1578
- **GitHub** - Devanand
