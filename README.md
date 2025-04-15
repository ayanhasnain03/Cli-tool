create-exs
create-exs is a command-line tool designed to quickly scaffold a Node.js backend project with customizable configurations. It offers support for technologies like MongoDB, GraphQL, CORS, Docker, ESLint, and more, based on your preferences. This CLI tool helps streamline the setup process and reduces manual configurations.

Installation
You can install create-exs globally via npm:


npm install -g create-exs
Alternatively, you can install it locally within your project:


npm install create-exs
Usage
After installing create-exs, you can run the tool using the following command:


npx create-exs
This will prompt you with several configuration questions to set up your project. You will be asked to choose options like:

Project name

Preferred language (JavaScript or TypeScript)

MongoDB, GraphQL, CORS, Docker, ESLint, and more options

Once the prompts are completed, the tool will generate a new project based on your choices.

CLI Questions
During the setup, the following questions will be asked:

Project Name
Choose a name for your project.

Preferred Language
Select between JavaScript or TypeScript.

Use MongoDB
Choose whether you want to use MongoDB as your database.

Use GraphQL
Enable GraphQL for API development.

Enable CORS
Configure Cross-Origin Resource Sharing (CORS).

Use Error Handler
Enable a basic error handler for your project.

Use Environment File
Configure .env for managing environment variables.

Use Morgan for Logging
Enable Morgan for logging HTTP requests.

Use Docker
Set up Docker for easy deployment.

Use ESLint
Enable ESLint for code linting.

Set Path Alias (@/ as src)
Configure @/ as a path alias when using TypeScript.

Auto-install Dependencies
Automatically install the dependencies after project setup.


npx create-exs
Once the setup is complete, you will have a fully configured Node.js backend project ready for development.

Project Structure
The generated project will include:

A basic Express setup

MongoDB, GraphQL, and CORS configurations if selected

Docker configuration for easy deployment

ESLint setup for code linting

Environment variable handling with .env

Project folder structure with the option to set @/ as a path alias in TypeScript

License
This project is licensed under the MIT License - see the LICENSE file for details.

Contributing
Feel free to fork this project and open a pull request if you have any improvements or bug fixes.

Author
Ayan Hasnain
