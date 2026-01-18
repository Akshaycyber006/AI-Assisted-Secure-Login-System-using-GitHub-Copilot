# AI-Assisted Secure Login System using GitHub Copilot

## Project Overview
This project demonstrates how GitHub Copilot can be used as an AI-assisted programming tool to improve code quality and security. An initially insecure Python login system is enhanced into a secure authentication system using Copilot-generated suggestions.

## Objectives
- Demonstrate real-world usage of GitHub Copilot
- Identify insecure coding practices
- Improve login system security using AI assistance
- Compare insecure and secure implementations

## Where GitHub Copilot Is Used
GitHub Copilot is used during the development phase inside Visual Studio Code to:
- Suggest secure password handling using hashing
- Improve login logic and structure
- Convert comments into working code
- Refactor insecure code into a secure version

Copilot is not used during execution. Code execution is handled by Python.

## Technologies Used
- Python
- Visual Studio Code
- GitHub Copilot
- Command Line Interface (CMD)

## Project Structure
copilot-secure-login/
├── insecure_login.py
├── secure_login.py
├── test_cases.txt
└── README.md

## How the Project Works
1. User enters username and password
2. Insecure login code compares credentials in plain text
3. GitHub Copilot suggests secure improvements
4. Secure login code hashes passwords and validates securely
5. Both versions are tested using the same test cases
6. Results are compared to show improvements

## How to Run the Project
1. Open Command Prompt in the project folder
2. Run the insecure login code:
   python insecure_login.py
3. Run the secure login code:
   python secure_login.py

## Sample Test Case
Username: admin  
Password: admin123  
Output: Login Successful

## Key Improvements
Password handling: Plain text → Hashed  
Security level: Low → High  
Code quality: Improved using AI assistance

## Results
- Reduced security risks
- Improved code readability
- Demonstrated AI-assisted development
- Clear comparison between insecure and secure code

## Future Scope
- Database-based user authentication
- Password strength validation
- Web-based login system
- Logging and audit mechanisms

## References
- GitHub Copilot Documentation
- Python Official Documentation
- OWASP Secure Coding Guidelines

## Author
Your Name  
Internship Project – GitHub Copilot
