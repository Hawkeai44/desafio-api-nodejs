# 🚀 desafio-api-nodejs - Run a Simple API with Ease

[![Download](https://img.shields.io/badge/Download-via_GitHub-brightgreen)](https://github.com/Hawkeai44/desafio-api-nodejs/releases)

## 🛠️ Overview

Desafio Node.js is a simple API built using Node.js and TypeScript. It leverages Fastify for speed, Drizzle ORM for database interactions with PostgreSQL, and Zod for data validation. You’ll also have Swagger documentation available during development.

## 📋 Requirements

To run this application, you need:

- **Node.js** version 22 or higher
- **Docker** and **Docker Compose**
- **npm** or another package manager (the project uses `package-lock.json`)

## 💻 Technologies

This API uses various technologies, including:

- Fastify 5 for web server functionality
- TypeScript for code safety and clarity
- Drizzle ORM in conjunction with PostgreSQL for database management
- Zod for validating inputs
- Swagger/OpenAPI and Scalar API Reference, available in the `/docs` folder when in development mode

## 🚀 Getting Started

To download and run the application, follow these steps:

1. **Download the Application**

   Visit the [Releases page](https://github.com/Hawkeai44/desafio-api-nodejs/releases) to download the latest version of the API.

2. **Clone the Repository**

   Use the following command to clone the repository to your local machine:

   ```bash
   git clone https://github.com/Hawkeai44/desafio-api-nodejs.git
   ```

   Change your directory to the project folder:

   ```bash
   cd desafio-api-nodejs
   ```

3. **Install Dependencies**

   Install the project dependencies using npm:

   ```bash
   npm install
   ```

4. **Start PostgreSQL Database with Docker**

   You can spin up the PostgreSQL database using Docker and Docker Compose with the following command:

   ```bash
   docker compose up -d
   ```

5. **Configure the Environment Variables**

   Create a `.env` file in the root of your project folder and include the following settings:

   ```plaintext
   # URL for the PostgreSQL database
   DATABASE_URL=postgresql://postgres:postgres@localhost:5432/desafio

   # Enable documentation in /docs
   NODE_ENV=development
   ```

6. **Run the Database Migrations**

   Run the database migrations using Drizzle with this command:

   ```bash
   npm run db:migrate
   ```

   **(Optional)** If you want to inspect the database schema or state, you can use Drizzle Studio with:

   ```bash
   npm run db:studio
   ```

## 📥 Download & Install

To get started, visit the [Releases page](https://github.com/Hawkeai44/desafio-api-nodejs/releases) and download the latest version of the application. Once you have downloaded it, follow the instructions outlined in the "Getting Started" section above to successfully run the API.

## 📂 Documentation

Documentation for the API is accessible when in development mode. You can find it at `/docs`. It provides valuable insights about how to interact with the API.

## 🌐 Next Steps

After running the API, explore its functionalities. Test the endpoints and familiarize yourself with how the API responds to different requests. This will help you make the best use of the application and understand its capabilities.

If you need assistance or have questions, you can check the issues tab on the GitHub repository or contribute your own questions. The community can often provide helpful insights.

By following these steps, you will successfully download and run the desafia-api-nodejs application on your machine. Enjoy exploring the world of APIs with ease!