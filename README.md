# E-Learning-Platform
# E-Learning Platform

This project is a fully functional **E-learning platform** built using **HTML**, **CSS**, **JavaScript**, **PHP**, **MySQL**, and **Apache**. The platform allows users to access educational content, manage courses, and interact with a dynamic web-based learning environment.

## Features

- **User Authentication**: Secure login and registration for students and instructors.
- **Course Management**: Admins can add, update, and delete courses.
- **Interactive Content**: Instructors can upload educational materials like videos, documents, and quizzes.
- **Responsive Design**: Optimized for both desktop and mobile views using Bootstrap for a modern UI/UX.
- **Database**: Stores user information, course details, and content using MySQL.

## Technologies Used

- **Front-End**: 
  - HTML, CSS, JavaScript
  - Bootstrap, jQuery, Font Awesome (for UI/UX enhancement)
- **Back-End**:
  - PHP (for server-side scripting and dynamic content generation)
- **Database**:
  - MySQL (for structured data storage and querying)
- **Web Server**:
  - Apache (for hosting the platform)

## Getting Started

### Prerequisites
Make sure you have the following software installed:
- Apache Web Server
- MySQL Database
- PHP
- A browser for testing

### Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/e-learning-platform.git
    ```

2. **Set up the database**:
   - Create a MySQL database and import the provided `lmd_db.sql` file to set up the necessary tables.
   
3. **Configure the PHP files**:
   - Update the database connection details in the `config.php` file (host, username, password, and database name).

4. **Run the server**:
   - Start the Apache server to serve the platform on `localhost`.

5. **Access the platform**:
   - Open your browser and visit `http://localhost/e-learning-platform` to start using the platform.

## Usage

- **Students**: Can browse courses, view course materials, and track their progress.
- **Instructors**: Can upload content, create quizzes, and manage courses.
- **Admins**: Can manage users, courses, and site settings.

## Acknowledgments

This project was built to enhance my skills in full-stack web development. Special thanks to the online resources and tutorials that helped throughout the development process.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
