create-exs
create-exs is a command-line tool designed to help you quickly scaffold a Node.js backend project with customizable configurations. It allows you to choose from a variety of technologies and features such as MongoDB, GraphQL, CORS, Docker, ESLint, and more. This tool streamlines the process of setting up a Node.js backend, reducing manual configurations and saving you time on repetitive tasks.

Features
Customizable Setup: Select which technologies and configurations to include in your project.

Support for Popular Tech: MongoDB, GraphQL, CORS, ESLint, Docker, and more.

Project Structure: Generate a well-organized project with best practices, including Docker and environment management.

Fast and Efficient: Automate the process of setting up your backend with just a few simple prompts.

Installation
You can install create-exs either globally or locally, depending on your needs.

Global Installation
To install create-exs globally on your machine, use the following command:

npm install -g create-exs
Local Installation
Alternatively, you can install create-exs locally within your project:

npm install create-exs
Usage
Once installed, you can scaffold a new project using the following command:

npx create-exs
create-exs will prompt you with a series of configuration questions to help tailor the setup to your needs. During the setup, you'll choose options for:

Project Name: Choose a name for your project.

Preferred Language: Select between JavaScript or TypeScript.

Use MongoDB: Decide if you want to integrate MongoDB for your database.

Use GraphQL: Enable GraphQL for API development.

Enable CORS: Set up Cross-Origin Resource Sharing (CORS) for your project.

Use Error Handler: Enable a basic error handler for managing errors.

Use Environment File: Automatically generate a .env file for environment variables.

Use Morgan for Logging: Enable Morgan for HTTP request logging.

Use Docker: Set up Docker for deployment.

Use ESLint: Set up ESLint for code linting to maintain code quality.

Set Path Alias: Optionally configure @/ as a path alias in TypeScript.

Auto-install Dependencies: Automatically install dependencies once the setup is complete.

After answering the prompts, create-exs will generate a fully configured Node.js backend project, ready for development.

Project Structure
The generated project includes:

Basic Express Setup: A ready-to-use Express server setup.

Optional Configuration for MongoDB: MongoDB integration (if selected).

GraphQL Setup: Optional configuration for setting up a GraphQL API (if selected).

CORS Configuration: Cross-Origin Resource Sharing setup for your backend.

Docker Support: A Dockerfile for containerized deployment.

ESLint Configuration: Code linting setup to help maintain code quality.

Environment Variable Management: A .env file for managing sensitive environment variables.

Folder Structure: Organized project structure with optional support for TypeScript path aliases (e.g., @/ for the src directory).

License
This project is licensed under the MIT License. See the LICENSE file for more details.

Contributing
Contributions are welcome! Feel free to fork this repository and open a pull request with your improvements or bug fixes. Here are a few ways you can contribute:

Submit bug fixes or enhancements.

Improve documentation.

Add new features or configurations.

Author
Ayan Hasnain
GitHub: @ayanhasnain03
LinkedIn: Ayan Hasnain

Example Workflow
Install create-exs globally or locally in your project.

Run npx create-exs to start the setup.

Choose your configuration options such as language, tech stack, etc.

Enjoy your fully-configured Node.js backend project.

Feel free to make further customizations, and happy coding!
