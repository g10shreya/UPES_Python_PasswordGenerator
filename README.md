# Password Generator Web Application

A simple and responsive password generator web app that allows users to generate secure passwords with customizable options. The app is built with:

- **Backend**: Python
- **Frontend**: HTML, CSS, JavaScript

**SCREENSHOTS**
1- The GUI
![image](https://github.com/user-attachments/assets/096576b7-8424-4f24-ae2a-50ef16e22014)


2- Generated password is displayed on the same window
![image](https://github.com/user-attachments/assets/09f0f3e1-c2d7-4159-b8be-da4f7035941a)


### Features

- **Generate Random Passwords**: Choose the length and include/exclude uppercase letters, numbers, and symbols.
- **Copy to Clipboard**: A button to easily copy the generated password to your clipboard.
- **Responsive Design**: The app is fully responsive, ensuring it works on both desktop and mobile devices.
- **Beautiful UI**: A clean and spacious user interface with a modern design using the color scheme of #30C3CD, #267C8F.

---

### Requirements

- Python 3.x
- No external dependencies are required. This project uses built-in Python libraries.

---

### Installation

1. **Clone the repository** or download the project files.

2. **Run the Python script** to start the backend server:
   bash
   python app.py

The server will start, and you'll be able to access the app at:
http://localhost:8000


**Usage**
Select the password length: Enter a number between 4 and 32 in the "Password Length" field.
Select options: Check the boxes to include uppercase letters, numbers, and symbols in the password.
Click "Generate Password": The app will generate a random password based on the selected options.
Copy to Clipboard: After the password is generated, click the "Copy to Clipboard" button to copy the password.

**Folder Structure**
/password-generator-app
│
├── app.py            # Backend Python script to serve the application
├── index.html        # Frontend HTML file
├── styles.css        # Styles for the frontend
└── README.md         # Project documentation
