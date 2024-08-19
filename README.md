# Discord Clone

This project is a clone of Discord, a popular messaging and communication platform, built using a modern tech stack. The application includes core features such as real-time messaging, channel management, and user roles.

## Tech Stack

- **NestJS**: A powerful backend framework used to structure and organize the server-side logic of the application.
- **GraphQL**: A query language for APIs that provides a more efficient, powerful, and flexible alternative to REST.
- **Prisma**: An ORM (Object-Relational Mapping) tool that simplifies database access, providing a type-safe API for database interactions.
- **Postgres**: A powerful, open-source relational database system used to store user data, messages, and channels.
- **React**: A JavaScript library for building user interfaces, used here to create the front-end of the application.
- **Mantine**: A React component library that provides a set of accessible and customizable components, enhancing the UI/UX of the application.

## Features

- **Real-Time Messaging**: Users can send and receive messages in real-time within channels, similar to Discord's functionality.
- **Channel Management**: Users can create, join, and manage different channels, organizing communication based on topics or groups.
- **User Roles**: Implementation of user roles to manage permissions and access control within the application.

## Installation and Setup

1. **Clone the repository:**

```bash
git clone https://github.com/your-username/discord-clone.git
cd discord-clone

# Navigate to the server directory and install dependencies
cd server
npm install

# Navigate to the client directory and install dependencies
cd ../client
npm install
```

2. **Set up the environment variables:**
Create a .env file in the server directory with the necessary environment variables, including the Postgres database connection URL.

3. **Run the application:**
```bash
# Start the server
cd server
npm run start:dev

# Start the client
cd ../client
npm start
```
