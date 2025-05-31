Cyber Threat Tracker
Cyber Threat Tracker is a modern web platform designed for reporting, tracking, and analyzing cyber threats across industries. It enables users and organizations to stay informed, collaborate, and respond quickly to emerging cyber risks.
________________________________________
Features
•	User registration and login with role-based access (User, Admin)
•	Admin dashboard for managing users, threats, and alerts
•	Users can submit, view, and search cyber threats
•	Admins can add, edit, and delete threats and alerts
•	Activity logging for important actions
•	Fully responsive UI using Bootstrap 5
________________________________________
Technologies Used
•	Frontend: HTML, CSS, Bootstrap 5
•	Backend: PHP
•	Database: MySQL
________________________________________
Setup Instructions
1. Clone the Repository
git clone https://github.com/yourusername/cyberthreat-tracker.git
2. Import the Database
•	Create a MySQL database named cyberthreat_db
•	Import the provided SQL schema into the database using phpMyAdmin or the MySQL command line
3. Configure the Database Connection
•	Open the file db_connect.php
•	Update the database credentials according to your environment (e.g., username, password)
4. Run Locally
•	Place the project folder inside the htdocs directory of your XAMPP installation
•	Start Apache and MySQL using XAMPP Control Panel
•	Open your browser and go to:
http://localhost/cyberthreat-tracker/
________________________________________
Folder Structure
File/Folder	Description
index.php	Landing page
user_register.php	User registration page
user_login.php	User login page
admin_login.php	Admin login page
admin_dashboard.php	Admin dashboard interface
user_dashboard.php	User dashboard interface
insert_threat.php	Form for users to report new threats
view_threats.php	Displays list of reported threats
search_threats_user.php	Search functionality for users
manage_threats_admin.php	Admin interface for managing all threats
add_threat.php	Admin form to add new threats
edit_threat.php	Admin form to edit existing threats
delete_threat.php	Admin action to delete threats
manage_alerts_admin.php	Admin interface for managing alerts
add_alert.php	Admin form to create alerts
edit_alert.php	Admin form to edit alerts
delete_alert.php	Admin action to delete alerts
style.css	Custom CSS styles

Authors
•	Ammar Kaleem
•	Abdullah Nasir
________________________________________
License
This project is intended for educational purposes only.
________________________________________
Stay Secure. Stay Ahead.
