
password_strength_checkers
Repository navigation
Code
Issues
Pull requests
password_strength_checkers/passwordchecker
/README.md
parimalanagaraj07
parimalanagaraj07
2 weeks ago
227 lines (149 loc) · 4.24 KB

Preview

Code

Blame
# Password Strength Checker

## Overview

Password Strength Checker is a GUI-based cybersecurity project developed using Python and Tkinter.  
The application analyzes the strength of passwords based on different security parameters and provides real-time feedback to users.

The project helps users create stronger and more secure passwords by checking password complexity, detecting weak/common passwords, and displaying suggestions for improvement.

---

# Features

- Password Strength Analysis
- Weak / Medium / Strong Password Detection
- Password Score Calculation
- Common Password Detection
- Real-Time Password Checking
- Show / Hide Password Option
- Progress Bar Strength Meter
- Password Improvement Suggestions
- Dark Cyberpunk User Interface
- Cursor Glitter Animation Effect

---

# Technologies Used

- Python
- Tkinter
- Regex (`re` module)
- ttk Progressbar

---

# Project Structure

```text
PasswordStrengthChecker/
│
├── main.py
└── README.md
Working Principle
The application checks passwords using the following conditions:

Minimum password length
Uppercase letters
Lowercase letters
Numbers
Special characters
Common weak password database
The program calculates a score based on these parameters and classifies the password as:

Weak
Medium
Strong
It also provides suggestions to improve password security.

Password Strength Levels
Score	Strength
0 – 2	Weak Password
3 – 4	Medium Password
5	Strong Password
Sample Password Testing
Password	Result
123456	Very Weak Password
Pari123	Medium Password
P@ri12345	Strong Password
Installation Guide
Step 1 — Install Python
Download and install Python from:

https://www.python.org

During installation:

Enable “Add Python to PATH”
Step 2 — Create Project Folder
Create a folder named:

PasswordStrengthChecker
Step 3 — Create Python File
Create a file named:

main.py
Paste the project code into this file.

Step 4 — Run the Application
Open terminal in the project folder and run:

python main.py
User Interface
The application interface includes:

Password Input Field
Show/Hide Password Button
Password Strength Result
Score Display
Progress Bar
Suggestion Panel
Animated Glitter Cursor Effect
Security Checks Performed
The project checks whether the password contains:

At least 8 characters
Uppercase letters
Lowercase letters
Numbers
Special characters
It also verifies whether the password exists in the weak/common password list.

Future Enhancements
The following features can be added in future versions:

Password Generator
Password Crack Time Estimator
Database Integration
User Login Authentication
Password History Storage
Light/Dark Theme Toggle
Advanced Cybersecurity Features
Learning Outcomes
Through this project, the following concepts were learned:

Python Programming
GUI Development using Tkinter
Regex Pattern Matching
Event Handling
Cybersecurity Basics
Password Security Validation
Real-Time User Interaction
Advantages
User-friendly interface
Real-time password analysis
Helps users create secure passwords
Beginner-friendly cybersecurity project
Lightweight and fast application
Limitations
Offline password analysis only
Does not connect to real password breach databases
Basic password scoring system
Conclusion
The Password Strength Checker project successfully analyzes password complexity and helps users improve password security practices. The project demonstrates the implementation of cybersecurity concepts using Python and Tkinter with an interactive graphical user interface.

Author
Developed by Vidhyalakshmi thirumalairaj 

License
This project is created for educational and learning purposes only.

# Commonpassword.py
