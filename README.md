# resume-builder
The Resume Builder is a web application built using the MERN stack (MongoDB, Express, React, Node.js). This project allows users to create, customize, and download their resumes. The application provides an easy-to-use interface with various templates and customization options.

Features
User Authentication: Secure user registration and login.
Profile Management: Users can manage their personal information, work experience, education, skills, and achievements.
Template Selection: Multiple professionally designed resume templates to choose from.
Real-Time Preview: Users can see a real-time preview of their resume as they edit.
Export Options: Download resumes in PDF format.
Responsive Design: Works seamlessly on desktops, tablets, and mobile devices.

Technologies Used
MongoDB: For storing user data and resume information.
Express: A Node.js framework used to build the backend API.
React: For building the user interface and managing the state of the application.
Node.js: For handling server-side logic.
Redux: For managing application state.
Mongoose: To interact with MongoDB in an object-oriented way.
JWT: For secure user authentication.
Axios: For making HTTP requests from React to the Express API.

Installation
Prerequisites
Node.js
MongoDB
npm or yarn

Steps
Clone the repository:
bash
Copy code
git clone https://github.com/Aakashrawat08/resume-builder.git
Navigate to the project directory:
bash
Copy code
cd resume-builder
Install dependencies for both frontend and backend:
bash
Copy code
cd client
npm install
cd ../server
npm install
Set up environment variables:
Create a .env file in the server directory.
Add the following:
env
Copy code
MONGO_URI=your-mongodb-uri
JWT_SECRET=your-jwt-secret
PORT=5000
Run the application:
In the server directory, start the backend server:
bash
Copy code
npm start
In the client directory, start the frontend:
bash
Copy code
npm start

Usage
Register or log in to your account.
Fill in your personal information, work experience, education, skills, and achievements.
Choose a template for your resume.
Preview your resume in real-time.

Contributing
Contributions are welcome! Please fork this repository and submit a pull request for any changes you'd like to make.


Contact
For any inquiries, please contact Aakash.