README
This is a Node.js application that uses the Onfido API to create an applicant and generate an SDK token. The application allows users to input their first name, last name and workflow id, and then displays the SDK token and workflow run ID on the page.

Requirements
Node.js
npm
Onfido API token

Installation
Clone the repository to your local machine
git clone https://github.com/<your-username>/onfido-nodejs-app.git

Install the necessary dependencies
npm install

Create a .env file in the root directory of the project and add your Onfido API token like this
ONFIDO_API_TOKEN=<your-api-token>

Start the server
npm start

Visit http://localhost:3000 in your browser to access the application

Usage
Input your first name, last name and workflow id in the form
Click the submit button
The SDK will be initialised and displayed on the page

Note
It is recommended to exclude the node_modules folder and the .env file in the .gitignore file.
You need to replace <your-api-token> and <your-username> with your Onfido API token and GitHub username respectively.

Contribute
If you would like to contribute to the development of this project, please fork the repository and make a pull request.