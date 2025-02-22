Secret Page Authorization
This repository contains a simple Node.js application that demonstrates basic authorization for accessing a secret page.

Features
Authorization Mechanism: Users must enter the correct password to access the secret page.
Password Validation: The application checks user input against a predefined password.
Installation
Clone the Repository:

bash
Copy
Edit
git clone https://github.com/Jayanti-j/secret_page.git
Navigate to the Project Directory:

bash
Copy
Edit
cd secret_page
Install Dependencies:

bash
Copy
Edit
npm install
Usage
Start the Application:

bash
Copy
Edit
node index.js
Access the Application:

Open your web browser and navigate to http://localhost:3000.

Authorize Access:

Enter the password ILoveProgramming when prompted to view the secret page.

File Structure
index.js: Main server file that sets up the application.
public/: Directory containing static assets.
solution.js: Contains the password validation logic.
.hintrc: Configuration file for code linting.
package.json: Metadata and dependencies for the project.
package-lock.json: Locks the versions of installed dependencies.
Dependencies
Node.js: JavaScript runtime environment.
Express: Web framework for Node.js.