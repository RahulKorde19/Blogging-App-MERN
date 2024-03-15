# Blogging-App-MERN

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![GitHub issues](https://img.shields.io/github/issues/RahulKorde19/Blogging-App-MERN.svg)](https://github.com/RahulKorde19/Blogging-App-MERN/issues)
[![GitHub stars](https://img.shields.io/github/stars/RahulKorde19/Blogging-App-MERN.svg)](https://github.com/RahulKorde19/Blogging-App-MERN/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/RahulKorde19/Blogging-App-MERN.svg)](https://github.com/RahulKorde19/Blogging-App-MERN/network)

Blogging-App-MERN is a MERN (MongoDB, Express.js, React, Node.js) stack application that empowers users to create, view, and search for blog posts. It incorporates robust user authentication using bcrypt, JWT, and cookies, allowing users to log in, register, and engage with the community through comments. Only the author of a post has the authority to update or delete it.

## Table of Contents
- [Installation](#installation)
- [Features](#features)
- [User Authentication](#user-authentication)
- [Contributing](#contributing)
- [License](#license)

## Installation

To set up Blogging-App-MERN locally, follow these comprehensive steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/RahulKorde/Blogging-App-MERN
   cd Blogging-App-MERN `

1.  Install dependencies for both the client and server:

    -   Navigate to the `client` directory and install client dependencies:


        `cd client
        npm install`

    -   Move back to the root directory and install server dependencies:


        `cd ..
        cd server
        npm install`



2.  Run the application:

    -   In the `client` directory:


        `cd client
        npm start`

    -   In the `server` directory:


        `cd ..
        cd server
        node app.js`

3.  Access the application:

    -   Open your browser and navigate to `http://localhost:3000` to view the Blogging-App-MERN application.

This setup process covers cloning the repository, installing dependencies. Make sure to follow each step carefully to ensure a smooth installation process. If you encounter any issues, refer to the documentation or seek help from the community.

# Features


## User Authentication:

-   Secure user authentication using bcrypt, JWT, and cookies.
-   Login and registration functionalities.

## Post Management:

-   Create and update posts using React Quill for an enhanced text editor experience.
-   Upload and display images.
  

# User Authentication

Blogging-App-MERN uses bcrypt for password hashing, JWT for secure user authentication, and cookies for a seamless user experience. 



License
-------

This project is licensed under the MIT License - see the [LICENSE](https://chat.openai.com/c/LICENSE) file for details.
