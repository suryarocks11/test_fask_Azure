# Flask Login App

Flask Login App is a simple web application built with Flask that allows users to log in and access restricted content. It includes basic login functionality and uses Bootstrap for styling.

## Features

- User login with email and password
- Validation of login credentials
- Access control to restricted content
- Styling with Bootstrap

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/MirelaManta/flask-wtforms.git
   ```

2. Navigate to the project directory:

   ```bash
   cd flask-wtforms
   ```

3. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Set the secret key:

   Update the `app.secret_key` in `main.py` with your desired secret key.

5. Start the application:

   ```bash
   python main.py
   ```

6. Open a web browser and visit `http://localhost:5000` to access the application.

## File Structure

The project structure is as follows:

- `main.py`: The main Flask application file.
- `base.html`: The base HTML template used by other templates.
- `index.html`: The home page template.
- `login.html`: The login page template.
- `success.html`: The template for successful login.
- `denied.html`: The template for denied access.
- `static/css/styles.css`: CSS styles for the application.

## Usage

1. Home Page:
   - Displays a welcome message and a login button.
   - Clicking the login button redirects to the login page.

2. Login Page:
   - Requires users to enter their email and password.
   - Validates the login credentials.
   - On successful login, displays the success page.
   - On failed login, displays the denied page.

3. Success Page:
   - Displays a secret message and an embedded GIF.

4. Denied Page:
   - Displays an access denied message and an embedded GIF.
   
## Skills Utilized

In this project, I utilized the following skills and technologies:

- `Python`: The core programming language used for backend development.
- `Flask`: A lightweight web framework used for building the web application.
- `Flask-WTF`: An extension for Flask that integrates WTForms, used for form handling.
- `WTForms`: A flexible forms validation and rendering library for Python.
- `Flask-Bootstrap`: An extension for Flask that integrates Bootstrap, used for styling the application.
- `HTML`: Used for creating the structure and content of web pages.
- `CSS`: Used for styling the web application and enhancing its visual appeal.

These skills and technologies enabled me to develop a simple yet functional web application for user login and access control. I gained hands-on experience in building Flask applications, handling forms, and integrating Bootstrap for a polished user interface.
