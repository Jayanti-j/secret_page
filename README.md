<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Secret Page Authorization</title>
</head>
<body>
    <h1>Secret Page Authorization</h1>
    <p>This repository contains a Node.js application that demonstrates a basic authorization mechanism for accessing a secret page.</p>
    
    <h2>Features</h2>
    <ul>
        <li><strong>Authorization Mechanism</strong>: Users must enter the correct password to access the secret page.</li>
        <li><strong>Password Validation</strong>: The application verifies user input against a predefined password.</li>
    </ul>
    
    <h2>Installation</h2>
    <ol>
        <li><strong>Clone the Repository</strong>:
            <pre><code>git clone https://github.com/Jayanti-j/secret_page.git</code></pre>
        </li>
        <li><strong>Navigate to the Project Directory</strong>:
            <pre><code>cd secret_page</code></pre>
        </li>
        <li><strong>Install Dependencies</strong>:
            <pre><code>npm install</code></pre>
        </li>
    </ol>
    
    <h2>Usage</h2>
    <ol>
        <li><strong>Start the Application</strong>:
            <pre><code>node index.js</code></pre>
        </li>
        <li><strong>Access the Application</strong>:
            <p>Open your web browser and navigate to <code>http://localhost:3000</code>.</p>
        </li>
        <li><strong>Authorize Access</strong>:
            <p>Enter the password <code>ILoveProgramming</code> when prompted to view the secret page.</p>
        </li>
    </ol>
    
    <h2>File Structure</h2>
    <ul>
        <li><code>index.js</code>: Main server file that sets up the application.</li>
        <li><code>public/</code>: Directory containing static assets.</li>
        <li><code>solution.js</code>: Contains the password validation logic.</li>
        <li><code>.hintrc</code>: Configuration file for code linting.</li>
        <li><code>package.json</code>: Metadata and dependencies for the project.</li>
        <li><code>package-lock.json</code>: Locks the versions of installed dependencies.</li>
    </ul>
    
    <h2>Dependencies</h2>
    <ul>
        <li><strong>Node.js</strong>: JavaScript runtime environment.</li>
        <li><strong>Express</strong>: Web framework for Node.js.</li>
    </ul>
    
    <h2>License</h2>
    <p>This project is licensed under the MIT License.</p>
    
    <hr>
    <p><strong>Note</strong>: This application is for educational purposes and demonstrates a basic authorization mechanism. For production applications, consider implementing more secure authentication and authorization methods.</p>
</body>
</html>

