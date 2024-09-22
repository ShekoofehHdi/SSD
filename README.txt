Project Structure:

app.py >> 
   - This is the main Flask application file.
   - It contains all the route definitions for user registration, login, password reset, file upload, and API endpoints.
   - It also handles the connection to the SQLite database, user authentication using `bcrypt`, and API token authentication.

templates/  directory
   This directory contains the HTML files
   - index.html>>  users can registration or login
   - register.html>>  new users can sign up 
   - login.html>> existing users enter their username and password to access the dashboard
   - dashboard.html>> displays after a successful login... contains a link for uploading files
   - resetpassword.html>> Users can reset their password 
   - upload.html>>  users can upload files to the server (a savfe upload in static/uploads/ directory)
   - database.db>> SQLite database that stores the user information 

How to Run the Project
	- Install all the dependencies listed in `requirements.txt` using this command in terminal or cmd: pip install -r 
        - Run the Flask app>> using this command in terminal or cmd: python app.py
        - go to http://127.0.0.1:5000/ in browser to interact with the app

Features
	- User Registration 
	- Login
	- logou
	- Password Reset
	- File Upload.


