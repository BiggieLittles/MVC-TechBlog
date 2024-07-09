My MVC Tech Blog
Welcome to the repository for My MVC Tech Blog! This project is an example of a technology blog built using the Model-View-Controller (MVC) architectural pattern. The blog allows users to read, create, update, and delete posts, as well as comment on posts. It showcases the usage of various technologies to build a full-stack web application.

Features
User Authentication: Secure user registration and login functionality.
CRUD Operations: Create, Read, Update, and Delete blog posts.
Comment System: Users can comment on blog posts.
Responsive Design: The blog is accessible on both desktop and mobile devices.
MVC Architecture: Separation of concerns with models, views, and controllers.
Technologies Used
Backend:
Framework: Express.js
Database: MongoDB
ORM: Mongoose
Authentication: Passport.js
Frontend:
Templating Engine: EJS
CSS Framework: Bootstrap
JavaScript: Vanilla JS
Tools & Platforms:
Version Control: Git
Deployment: Heroku
Getting Started
Prerequisites
Make sure you have the following installed on your local machine:

Node.js
MongoDB
Installation
Clone the repository:

sh
Copy code
git clone https://github.com/yourusername/mvc-tech-blog.git
cd mvc-tech-blog
Install dependencies:

sh
Copy code
npm install
Set up environment variables:
Create a .env file in the root directory and add the following:

makefile
Copy code
MONGODB_URI=<Your MongoDB URI>
SESSION_SECRET=<Your Session Secret>
Start the application:

sh
Copy code
npm start
Access the application:
Open your browser and go to http://localhost:3000

Project Structure
bash
Copy code
mvc-tech-blog/
│
├── config/
│   └── db.js          # Database configuration
│
├── controllers/
│   ├── authController.js
│   ├── postController.js
│   └── commentController.js
│
├── models/
│   ├── User.js
│   ├── Post.js
│   └── Comment.js
│
├── public/
│   ├── css/
│   └── js/
│
├── routes/
│   ├── index.js
│   ├── auth.js
│   ├── posts.js
│   └── comments.js
│
├── views/
│   ├── auth/
│   ├── posts/
│   ├── comments/
│   └── partials/
│
├── .env
├── .gitignore
├── app.js             # Main application file
├── package.json
└── README.md
Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Contact
If you have any questions, feel free to contact me at homedog833@gmail.com.
