# SearchInDB

This is a simple Express.js project template for building web applications. It comes pre-configured with essential middleware and routing setup to help you get started quickly.

It has an EJS view engine, a MongoDB database, and a Node.js built-in HTTP server.

It alwas you to search in the database.

# Features

1. dotenv Configuration: Utilizes dotenv for managing environment variables.
2. Error Handling: Includes error handling middleware to catch and handle errors gracefully.
3. MVC Structure: Follows the Model-View-Controller pattern for organizing code.
4. Static File Serving: Serves static files from the public directory.
5. Logging: Utilizes Morgan for HTTP request logging.
6. View Engine: Configured with EJS (Embedded JavaScript) as the view engine.
7. Routing: Provides a basic index route setup.

# Installation

1. Clone this repository to your local machine.
2. Navigate to the project directory.
3. Install dependencies using npm:

```bash
npm install
```

# Usage

1. Start the server using:

```bash
npm start
```

2. Open http://localhost:3000 in your browser.

# Configuration

1. Create a .env file in the project directory.
2. Define environment variables in the .env file following the format: `KEY=VALUE`.

# Folder Structure

```bash
├── public/         # Static files (images, CSS, JavaScript)
├── routes/         # Route handlers
│   └── index.js    # Main route handler
├── views/          # EJS view files
│   ├── error.ejs   # Error page template
│   └── index.ejs   # Main index page template
├── .env            # Environment variables configuration
├── app.js          # Main application entry point
└── package.json    # Project metadata and dependencies
```

# License

This project is licensed under the MIT license.

# Contributing

Feel free to contribute to this project.

# Author

[SearchInDB](https://github.com/anonymus1145/SearchInDB.git)