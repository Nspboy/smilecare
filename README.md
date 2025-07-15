# SmileCare - Dental 

SmileCare is a web-based Hospital Management System built using PHP and MySQL. It provides comprehensive management for hospitals, doctors, patients, and medical histories. The system is designed to be deployed locally for easy access and management of hospital operations.

## Features

- **User Roles:** Supports Admin, Doctor, and Patient roles with independent logins.
- **Patient Management:** Doctors can add, view, and manage patient records.
- **Medical History Tracking:** Users can view and manage medical histories linked to patients.
- **Authentication:** Secure login system for all roles.
- **Responsive UI:** Uses Bootstrap and modern web technologies for a user-friendly interface.

## Installation & Setup

1. **Download the Project**
   - Download the zip file of the repository.

2. **Extract & Copy**
   - Extract the file and copy the `hospital` folder.

3. **Paste to Server Directory**
   - For XAMPP: Paste inside `xampp/htdocs`
   - For WAMP: Paste inside `wamp/www`
   - For LAMP: Paste inside `var/www/html`

4. **Setup the Database**
   - Open PHPMyAdmin (`http://localhost/phpmyadmin`)
   - Create a database named `hms`
   - Import the `hms.sql` file (located inside the SQL file folder of the zip package)

5. **Run the Application**
   - Visit: `http://localhost/hospital` in your browser to access the frontend

## Login Details

- **Admin:**  
  Username: `admin`  
  Password: `Test@12345`

- **Patient:**  
  Email: `johndoe12@test.com`  
  Password: `Test@123`

- **Doctor:**  
  Email: `anujk123@test.com`  
  Password: `Test@123`

## Technologies Used

- PHP
- MySQL
- Bootstrap
- jQuery

## Project Structure

- `assets/` - Contains CSS, JS, and images
- `include/` - Common header, sidebar, and config files
- Main PHP files for managing patients, medical history, user authentication, etc.

## License

This project currently does not have a license. Please add one if you intend to share or modify.

---

For any issues or feature requests, please use the GitHub Issues section.
