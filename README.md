# mawd-14
MVC challenge
Tech Blog CMS
Welcome to the Tech Blog CMS! This project is a CMS-style blog site where developers can publish their blog posts and interact with other developers’ posts. Built from scratch following the Model-View-Controller (MVC) paradigm, this web application is designed to provide a seamless experience for both content creators and readers.

Features
User Authentication: Users can sign up for an account or log in if they already have one. Authentication ensures that only authorized users can access certain functionalities.
Homepage with Existing Blog Posts: Upon visiting the site, users are presented with the homepage featuring existing blog posts, if any have been published.
Dashboard: Authenticated users have access to a dashboard where they can manage their blog posts. They can view existing posts, create new ones, update, or delete them.
Commenting System: Users can engage with blog posts by leaving comments. Comments are displayed below each post, enhancing interactivity.
Session Management: Users are logged out automatically after a set time of inactivity to ensure security.
Responsive Design: The application is designed to be responsive, providing an optimal viewing and interaction experience across a wide range of devices.
Technologies Used
Handlebars.js: Used as the templating engine for generating HTML content.
Sequelize: An ORM (Object-Relational Mapping) used for interacting with the database.
Express.js: A web application framework for Node.js used for building the backend server.
Express-session: Middleware for managing sessions in Express applications, used for authentication.
MySQL: A relational database management system used to store user data, blog posts, and comments.
Getting Started
To run this project locally, follow these steps:

Clone the repository: git clone git@github.com:ZachariahKB/mawd-14.git
Navigate to the project directory: cd mawd-14
Install dependencies: npm install
Set up the database:
Create a MySQL database.
Update the database configuration in config/config.json.
Run migrations to create the necessary tables: npx sequelize-cli db:migrate
Start the server: npm start
Access the application in your web browser at http://localhost:3001
Contributing
Contributions are welcome! If you'd like to contribute to this project, please follow these guidelines:

Fork the repository.
Create your feature branch: git checkout -b feature-name
Commit your changes: git commit -am 'Add some feature'
Push to the branch: git push origin feature-name
Submit a pull request.
License
This project is licensed under the MIT License.

Contact
For any inquiries or feedback, feel free to contact us.

