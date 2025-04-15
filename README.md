# create-exs

**create-exs** is a command-line tool designed to quickly scaffold a Node.js backend project with customizable configurations. It offers support for technologies like MongoDB, GraphQL, CORS, Docker, ESLint, and more, based on your preferences. This CLI tool helps streamline the setup process and reduces manual configurations.

---

## Installation

### Global Installation
Install **create-exs** globally using npm:

```bash
npm install -g create-exs
Local Installation
Alternatively, install it locally within your project:


npm install create-exs
Usage
After installing, you can run the tool using:

npx create-exs
The CLI will prompt you with several configuration questions to set up your Node.js backend project. You’ll choose options for:

Project Name: Choose a name for your project.

Preferred Language: Select between JavaScript or TypeScript.

Use MongoDB: Decide if you want to integrate MongoDB.

Use GraphQL: Enable GraphQL for API development.

Enable CORS: Configure Cross-Origin Resource Sharing.

Use Error Handler: Set up a basic error handler.

Use Environment File: Create a .env file for environment variables.

Use Morgan for Logging: Enable Morgan for HTTP request logging.

Use Docker: Set up Docker for deployment.

Use ESLint: Enable ESLint for code linting.

Set Path Alias (@/ as src): Configure @/ as a path alias in TypeScript.

Auto-install Dependencies: Automatically install dependencies once the setup is complete.

After answering the prompts, create-exs will generate a fully configured Node.js backend project, ready for development.

Project Structure
The generated project includes:

A basic Express setup.

Optional configuration for MongoDB, GraphQL, and CORS.

Docker configuration for easy deployment.

ESLint configuration for code linting.

Environment variable management using a .env file.

A project folder structure with an option for a @/ path alias in TypeScript.

License
This project is licensed under the MIT License — see the LICENSE file for details.

Contributing
Contributions are welcome! Feel free to fork this repository and open a pull request with your improvements or bug fixes.

Author
Ayan Hasnain

You can paste this content into your `README.md` file to provide comprehensive and attractive documentation for your CLI tool.




