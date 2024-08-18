Quiz Application
A dynamic quiz application that allows users to answer questions, with the layout featuring questions displayed on the left side and an OMR sheet on the right side for selecting answers.

Table of Contents
Project Overview
Features
Technology Stack
Installation
Usage
Database Schema
Folder Structure
Contributing
License
Contact
Project Overview
This project is a web-based quiz application built with PHP, MySQL, and JavaScript. The application dynamically loads questions and displays them on the left section of the page. The right section acts as an OMR sheet where users can select answers using radio buttons, with a clean and responsive design using Bootstrap.

Features
Dynamic Question Loading: Questions are loaded dynamically from a MySQL database.
Interactive OMR Sheet: Radio buttons for selecting answers are displayed in a clean OMR-like format.
Responsive Design: The application is fully responsive, ensuring a seamless experience across devices.
Timer Functionality: A timer is displayed to keep track of the quiz duration.
Navigation Controls: Users can navigate between questions using Previous and Next buttons.

Technology Stack
Frontend:
HTML5
CSS3 (Custom Styles + Bootstrap 4)
JavaScript (with Fetch API for AJAX calls)
Bootstrap Icons (via CDN)
Backend:
PHP (for server-side scripting)
MySQL (for database management)
Development Tools:
Visual Studio Code (VS Code)
XAMPP/WAMP (for local development environment)
Git (for version control)
Installation
Prerequisites:
PHP (7.4+)
MySQL (5.7+)
XAMPP/WAMP for local development

Steps:
Clone the Repository:

git clone https://github.com/your-username/quiz-application.git
Navigate to the Project Directory:


cd quiz-application
Set Up the Database:

Import the database.sql file provided in the db folder into your MySQL database.
Configure the database connection settings in right12.php (or other PHP files).
Start the Development Server:

If using XAMPP or WAMP, place the project folder in the htdocs directory.
Start Apache and MySQL services from the XAMPP/WAMP control panel.
Access the application at http://localhost/quiz-application.
Usage
Open the application in a web browser.
Select the desired quiz and start answering the questions.
Use the OMR sheet on the right to mark your answers.
Submit the quiz once all questions are answered.
Database Schema
Tables:
test:

testid: INT, Primary Key
testname: VARCHAR(255)
userquiz:

id: INT, Auto Increment, Primary Key
userid: INT
testid: INT
questionno: INT
option: VARCHAR(10)
Folder Structure

quiz-application/

│
├── db/
│   └── database.sql       
│
├── css/
│   └── styles.css         
│
├── js/
│   └── script.js         
├── right12.php            
├── index.html             
└── README.md   

Contributing
Contributions are welcome! Please follow these steps:

Fork the repository.
Create a new branch (git checkout -b feature-branch).
Commit your changes (git commit -m 'Add some feature').
Push to the branch (git push origin feature-branch).
Open a pull request.
License
This project is licensed under the MIT License - see the LICENSE file for details.

Contact
If you have any questions or suggestions, feel free to contact me:

Email: vedhasreeg51@gmail.com

GitHub: VEDHA SREE G
