# Project-News-Headdlines-Console-Screen-With-log-in-And-API-Intrigation
A Python-based console application that allows users to log in, register, reset passwords, and fetch the latest news headlines using the NewsAPI. 
The project demonstrates user authentication, secure password handling, and API integration in a simple console-based interface.


                                                               Features

User Registration: Register new users with email and secure hashed passwords.

Login Functionality: Authenticate registered users with their credentials.

Password Recovery: Reset forgotten passwords using security questions.

News Fetching: Retrieve the latest news headlines based on keywords using the NewsAPI.

Secure Storage: Store user credentials securely in a CSV file.

Prerequisites

To run this application, you need:

Python 3.7 or higher

requests library

Install the required library with the following command:
pip install requests

Setup Instructions
1.) Replace the api_key variable in the fetch_news function with your NewsAPI key:
api_key = "your_api_key_here"
Get your free API key from NewsAPI.

2.) Run the application:
python app.py

                                                                Usage

1- Register a New User:

Select the option to register a new user.

Enter your email, password, and a security question.

2- Login:

Log in using your registered email and password.

If successful, you can enter a keyword to fetch the latest news headlines.

3- Forgot Password:

Select the option to reset your password.

Answer the security question correctly to set a new password.

4- Fetch News:

After logging in, enter a keyword or topic to retrieve the top 5 latest news headlines from trusted sources.

Code Structure-

app.py: Main script to run the application.

12324729.csv: CSV file to store user credentials securely.

Functions include:

add_user: Register a new user.

validate_login: Authenticate users.

forgot_password: Reset user passwords.

fetch_news: Fetch news headlines using the NewsAPI.

Example - 
1- Run the application and choose to register a user:
Enter your email: example@example.com
Enter your password: strongpassword@123
Enter your security question: What is your pet's name?
User registered successfully!

2- Login:
Enter your email: example@example.com
Enter your password: strongpassword@123
Enter a keyword or topic: football

Output like this:
Headline 1 - Source 1
Headline 2 - Source 2
Headline 3 - Source 3
Headline 4 - Source 4
Headline 5 - Source 5

Acknowledgments:
NewsAPI for providing access to global news headlines.

Python community for libraries and inspiration.



