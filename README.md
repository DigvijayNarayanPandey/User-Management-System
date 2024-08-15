# User Management System

A web application for managing user profiles, built with Node.js, Express, and MongoDB. This application allows users to create, read, update, and delete profiles.

## Features

- **Create User**: Add new user profiles with name, email, and image URL.
- **Read Users**: View a list of all user profiles.
- **Update User**: Edit user details.
- **Delete User**: Remove user profiles.

## Technologies Used

- **Node.js**: JavaScript runtime for server-side development.
- **Express**: Web framework for Node.js.
- **MongoDB**: NoSQL database for storing user data.
- **EJS**: Embedded JavaScript templating engine for rendering HTML.
- **Tailwind CSS**: Utility-first CSS framework for styling.

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/user-management-system.git
   ```
   
2. **Navigate to the project directory:**

   ```bash
   cd user-management-system
   ```
3. **Install dependencies:**

   ```bash
   npm install
   ```
4. **Start MongoDB server:**
   
   Ensure MongoDB is running locally. You can start it with:
   
   ```bash
   mongod
   ```
   5. **Start the application:**
   ```bash
   npm start
   ```
   *The application will be available at http://localhost:8080.*
   
**Usage**  

- **Homepage (/)**: Navigate to the home page.
- **Read Users (/read)**: View the list of users.
- **Create User (/create)**: Use the form to add a new user.
- **Edit User (/edit/:userid)**: Update an existing user's details.
- **Delete User (/delete/:id)**: Remove a user from the list.
  
**Contributing**  

Feel free to open issues or submit pull requests if you'd like to contribute to the project.  

  
**License**  

This project is licensed under the MIT License. See the LICENSE file for details.  

  

**Acknowledgments**  

- **Tailwind CSS for the styling.**
**EJS for templating.**
   

