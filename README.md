# Car Rental Portal

Welcome to the **Car Rental Portal** project! This is a web-based application designed for car rental businesses of all sizes. The system allows users to view, book, and manage rental cars, while providing a complete set of admin features to handle vehicle listings, bookings, and customer management.

## Table of Contents
- [Project Overview](#project-overview)
- [Technologies Used](#technologies-used)
- [Features](#features)
  - [Guest Users](#guest-users)
  - [Registered Users](#registered-users)
  - [Admin](#admin)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Project Overview
This project is a fully functional car rental portal developed using PHP and MySQL. It features a responsive interface, allowing users to easily navigate through car listings, make bookings, and manage their profiles. The system includes different access levels for users and administrators to ensure seamless management of the platform.

The repository for this project can be found here: [Webstack-Portfolio-Project](https://github.com/AbelAsiedu/Webstack-Portfolio-Project.git).

## Technologies Used
- **Backend**: PHP (versions 5.2, 7.5, and 8.2)
- **Frontend**: HTML, CSS, JavaScript, jQuery, AJAX
- **Database**: MySQL (versions 5.x and 8.x)
- **Server**: XAMPP / WAMP / MAMP / LAMP (any local server setup)
- **Web Browsers Supported**: Chrome, Mozilla Firefox, IE8, Opera

## Features

### Guest Users
- View car listings and details.
- Make inquiries via the contact form.
- Register to become a user.

### Registered Users
- Log in to their account.
- Book available cars.
- View their booking history.
- Update profile information and change their password.
- Post testimonials.
- Log out.

### Admin
- Manage vehicle brands and listings (add, edit, and delete).
- View and manage car bookings (approve or cancel).
- Manage user accounts.
- Post and manage testimonials (activate/deactivate).
- View contact queries.
- Manage site subscribers.
- View admin dashboard statistics (registered users, bookings, subscribers, etc.).
- Update site content and contact details.

## Installation

### Prerequisites
- Ensure you have a local server setup such as XAMPP, WAMP, MAMP, or LAMP installed.
- Make sure you have PHP and MySQL installed.

### Steps to Install

1. Clone the repository:
   ```bash
   git clone https://github.com/AbelAsiedu/Webstack-Portfolio-Project.git


   
Move the project folder to the root directory of your server:
mv Webstack-Portfolio-Project /path-to-your-server-root/carrental
Open PHPMyAdmin and create a database named carrental.

Import the database:

Navigate to the carrental.sql file located in the project directory.
Import the file into the carrental database you just created.
Configure the database connection:

Go to the /config/database.php file and update the database credentials to match your local setup.
Start the server and visit:
http://localhost/carrental

Use the following credentials to log in:

Admin:

Username: admin
Password: Test@12345
User:

Username: test@gmail.com
Password: Test@123
Usage
Guest Users can explore car listings and sign up to access more features.
Registered Users can book cars, view their booking history, and post testimonials.
Admin has full control over the platform, including managing cars, bookings, and users.
Contributing
Contributions are welcome! If you want to contribute to this project, please follow these steps:

Fork the repository.
Create a new feature branch (git checkout -b feature-branch).
Commit your changes (git commit -m "Add new feature").
Push to the branch (git push origin feature-branch).
Create a pull request.

Memory updated
Here’s a well-structured README.md for your Car Rental Portal project on GitHub:

md
Copy code
# Car Rental Portal

Welcome to the **Car Rental Portal** project! This is a web-based application designed for car rental businesses of all sizes. The system allows users to view, book, and manage rental cars, while providing a complete set of admin features to handle vehicle listings, bookings, and customer management.

## Table of Contents
- [Project Overview](#project-overview)
- [Technologies Used](#technologies-used)
- [Features](#features)
  - [Guest Users](#guest-users)
  - [Registered Users](#registered-users)
  - [Admin](#admin)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Project Overview
This project is a fully functional car rental portal developed using PHP and MySQL. It features a responsive interface, allowing users to easily navigate through car listings, make bookings, and manage their profiles. The system includes different access levels for users and administrators to ensure seamless management of the platform.

The repository for this project can be found here: [Webstack-Portfolio-Project](https://github.com/AbelAsiedu/Webstack-Portfolio-Project.git).

## Technologies Used
- **Backend**: PHP (versions 5.6, 7.x, and 8.x)
- **Frontend**: HTML, CSS, JavaScript, jQuery, AJAX
- **Database**: MySQL (versions 5.x and 8.x)
- **Server**: XAMPP / WAMP / MAMP / LAMP (any local server setup)
- **Web Browsers Supported**: Chrome, Mozilla Firefox, IE8, Opera

## Features

### Guest Users
- View car listings and details.
- Make inquiries via the contact form.
- Register to become a user.

### Registered Users
- Log in to their account.
- Book available cars.
- View their booking history.
- Update profile information and change their password.
- Post testimonials.
- Log out.

### Admin
- Manage vehicle brands and listings (add, edit, and delete).
- View and manage car bookings (approve or cancel).
- Manage user accounts.
- Post and manage testimonials (activate/deactivate).
- View contact queries.
- Manage site subscribers.
- View admin dashboard statistics (registered users, bookings, subscribers, etc.).
- Update site content and contact details.

## Installation

### Prerequisites
- Ensure you have a local server setup such as XAMPP, WAMP, MAMP, or LAMP installed.
- Make sure you have PHP and MySQL installed.

### Steps to Install

1. Clone the repository:
   ```bash
   git clone https://github.com/AbelAsiedu/Webstack-Portfolio-Project.git
Move the project folder to the root directory of your server:

bash
Copy code
mv Webstack-Portfolio-Project /path-to-your-server-root/carrental
Open PHPMyAdmin and create a database named carrental.

Import the database:

Navigate to the carrental.sql file located in the project directory.
Import the file into the carrental database you just created.
Configure the database connection:

Go to the /config/database.php file and update the database credentials to match your local setup.
Start the server and visit:

bash
Copy code
http://localhost/carrental
Use the following credentials to log in:

Admin:

Username: admin
Password: Test@12345
User:

Username: test@gmail.com
Password: Test@123
Usage
Guest Users can explore car listings and sign up to access more features.
Registered Users can book cars, view their booking history, and post testimonials.
Admin has full control over the platform, including managing cars, bookings, and users.
Contributing
Contributions are welcome! If you want to contribute to this project, please follow these steps:

Fork the repository.
Create a new feature branch (git checkout -b feature-branch).
Commit your changes (git commit -m "Add new feature").
Push to the branch (git push origin feature-branch).
Create a pull request.
License
This project is open-source and available under the MIT License.
