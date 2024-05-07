# MERN Stack Real-Time Chat App

This project is a real-time chat application built using the MERN stack (MongoDB, Express.js, React.js, Node.js) along with Socket.io for real-time messaging. It also utilizes TailwindCSS for styling and Daisy UI for additional UI components.
![UI](https://github.com/IsaacHevi/Chat-App/assets/142832860/c4cd65a7-09a5-4833-8fd5-fb5df29dfe59)
![Login UI](https://github.com/IsaacHevi/Chat-App/assets/142832860/e45a259b-3a07-47c7-aca5-541315492bfa)

## Features

- **Authentication & Authorization**: Users can sign up, log in, and authenticate using JSON Web Tokens (JWT).
- **Real-time Messaging**: Utilizes Socket.io for real-time messaging between users.
- **Online User Status**: Displays online status of users using Socket.io and React Context.
- **Global State Management**: Zustand is used for managing global state within the application.
- **Error Handling**: Provides error handling both on the server and client sides for a smooth user experience.
- **Environment Variables**: Utilizes a `.env` file for managing environment variables such as port, MongoDB URI, JWT secret, and Node environment.

## Tech Stack

- **Frontend**: React.js, Socket.io-client, TailwindCSS, Daisy UI
- **Backend**: Node.js, Express.js, Socket.io, MongoDB
- **State Management**: Zustand
- **Authentication**: JSON Web Tokens (JWT)
- **Styling**: TailwindCSS, Daisy UI

## Getting Started

### Prerequisites

- Node.js installed on your machine
- MongoDB Atlas account (for hosting the database)

### Setup

1. Clone the repository:

    ```bash
    git clone <repository-url>
    ```

2. Navigate to the project directory:

    ```bash
    cd mern-realtime-chat
    ```

3. Install dependencies for both frontend and backend:

    ```bash
    cd /frontend && npm install
    cd ../backend && npm install
    ```

4. Create a `.env` file in the `root` directory and configure the following environment variables:

    ```
    PORT=... # Port number for the server
    MONGO_DB_URI=... # MongoDB URI for connecting to the database
    JWT_SECRET=... # Secret for generating JWT tokens
    NODE_ENV=... # Node environment (e.g., development, production)
    ```

5. Build the app:

    ```bash
    npm run build
    ```

6. Start the app:

    ```bash
    npm start
    ```

7. Access the application in your browser at `http://localhost:<PORT>`.
