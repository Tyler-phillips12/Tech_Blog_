## Tech_Blog 
This is a CMS-style blog site that allows users to create, view, update, and delete blog posts. The site also provides functionality for user authentication and commenting on blog posts.

The CMS-style blog site is designed to provide a user-friendly platform for creating and managing blog posts. Users can sign up, log in, and perform various actions such as creating new posts, updating existing posts, and leaving comments on posts. The site also includes features like user authentication, session management, and automatic logout after a period of inactivity.

# Features
The blog site offers the following features:

User authentication: Users can sign up with a unique username and password.
User session management: Users remain logged in until they choose to log out or become idle for an extended period.
Homepage: The homepage displays existing blog posts and provides navigation links to the homepage, dashboard, and login/logout options.
View blog posts: Users can view blog posts on the homepage, including the post title, date created, and post contents.
Commenting: Users can leave comments on existing blog posts.
Dashboard: The dashboard allows users to view and manage their own blog posts, including the option to add new posts, update existing posts, or delete posts.
# Usage
When you visit the site for the first time:

1. You are presented with the homepage, which displays existing blog posts (if any), navigation links to the homepage and dashboard, and the option to log in.
2. Clicking on the homepage option takes you to the homepage.
3. Clicking on any other links in the navigation prompts you to sign up or sign in.

If you choose to sign up:

1. You are prompted to create a unique username and password.
2. Clicking on the sign-up button saves your user credentials and logs you into the site.
When you revisit the site and choose to sign in:

1. You are prompted to enter your username and password.
2. If your credentials are valid, you are signed in and see navigation links for the homepage, dashboard, and the option to log out.

While signed in:

1. Clicking on the homepage option takes you to the homepage and presents existing blog posts that include the post title and the date created.

2. Clicking on an existing blog post presents the post title, contents, post creator's username, and date created. You also have the option to leave a comment.

3. When you enter a comment and click on the submit button while signed in, the comment is saved, and the post is updated to display the comment, the comment creator's username, and the date created.

4. Clicking on the dashboard option in the navigation takes you to the dashboard and presents any blog posts you have already created. You also have the option to add a new blog post.

5. Clicking on the button to add a new blog post prompts you to enter both a title and contents for your blog post.

6. Clicking on the button to create a new blog post saves the title and contents of your post and takes you back to an updated dashboard with your new blog post.

7. Clicking on one of your existing posts in the dashboard allows you to delete or update your post and takes you back to an updated dashboard.

8. Clicking on the logout option in the navigation signs you out of the site.

If you are idle on the site for more than a set time, you can still view posts and comments, but you are prompted to log in again before you can add, update, or delete posts.

# Technologies
The CMS-style blog site is built using the following technologies:

Front-end: HTML, CSS, JavaScript
Back-end: Node.js, Express.js
Database: MySQL, Sequelize ORM
User authentication: Passport.js
Session management: Express-session

# Installation
To run the CMS-style blog site locally, you need to have Node.js and MySQL installed on your machine. Follow these steps:

1. Clone this repository to your local machine.
2. Install the dependencies by running the following command:
npm install
3. Create a MySQL database and update the configuration in the config/config.js file.
4. Run the database migrations using the following command:

npx sequelize-cli db:migrate
5. Start the server by running the following command:
sql
npm start
6. Open your web browser and access the site at http://localhost:3001.
# Contributing
Contributions to the CMS-style blog site are welcome. If you find any bugs or have suggestions for improvements, please create an issue or submit a pull request.

# License
This project is licensed under the MIT License.
