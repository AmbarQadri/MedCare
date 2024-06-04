# MedCare

MedCare is a health website aimed at providing convenient access to healthcare services. It is built using HTML, CSS, and JavaScript for the frontend, and PHP for the backend. The website features online doctor appointment scheduling, online payments, hospital search, user login, and registration.

## Features

- **Online Doctor Appointment:** Users can schedule appointments with doctors online.
- **Payment:** Online payment feature for appointments and services.
- **Hospital Search:** Users can search for hospitals based on location and services.
- **Login and Register:** Secure user authentication for accessing personalized features.

## Usage

- Register as a new user or log in if you already have an account.
- Search for hospitals by location or services offered.
- Schedule an appointment with a doctor.
- Make online payments for appointments and services.

## Getting Started

### Prerequisites

Before running the project, you need to have the following installed:

- [PHP](https://www.php.net/downloads)
- [MySQL](https://www.mysql.com/downloads/)
- A web server like [Apache](https://httpd.apache.org/download.cgi) or [Nginx](https://nginx.org/en/download.html)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/AmbarQadri/MedCare.git

2. Navigate to the project directory:

   ```bash
   cd MedCare
   ```

3. Import the database.sql file into your MySQL database to set up the database schema.

4. Update the database configuration in config.php with your MySQL database credentials:

   ```php
   define('DB_SERVER', 'localhost');
   define('DB_USERNAME', 'root');
   define('DB_PASSWORD', '');
   define('DB_NAME', 'medcare');
   ```

5. Start your web server.

6. Open your browser and visit http://localhost/MedCare to view the website.

## Technologies Used

- HTML
- CSS
- JavaScript
- PHP
- MySQL
  
