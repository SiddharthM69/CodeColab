# CodeCollab - Collaborative Online Code Editor

![CodeCollab Logo](link/to/logo.png)

CodeCollab is a powerful and collaborative online code editor built with ReactJS and NodeJS. It allows multiple developers to work together in real-time, enhancing team productivity and making remote collaboration seamless.

## Features

- **Real-time Collaboration:** CodeCollab enables multiple developers to code together in real-time. Changes made by one user are instantly reflected for others, fostering effective collaboration.

- **Syntax Highlighting:** The editor supports syntax highlighting for various programming languages, making code reading and writing more comfortable.

- **Multi-Language Support:** CodeCollab supports a wide range of programming languages, ensuring that developers can work on projects using their preferred language.

- **Version Control Integration:** Seamlessly integrate with popular version control systems like Git, allowing developers to manage their codebase efficiently.

- **Code Sharing:** Easily share your code with others by generating a shareable link. This is especially useful for quick collaboration or seeking assistance from team members.

- **User Authentication:** Securely authenticate users to ensure that only authorized individuals can access and edit the codebase.

## Getting Started

To run CodeCollab locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/SiddharthM69/CodeColab.git
   ```

2. Install dependencies for both the client and server:

   ```bash
   cd codecollab/editor
   npm install

   cd ../editor-backend
   npm install
   ```

3. Start the development servers:

   ```bash
   # In the client directory
   npm start

   # In the server directory
   npm start
   ```

4. Open your browser and navigate to [http://localhost:3000](http://localhost:3000) to use CodeCollab locally.

## Technologies Used

- **ReactJS:** A JavaScript library for building user interfaces, providing a fast and efficient way to create interactive applications.

- **NodeJS:** A JavaScript runtime built on Chrome's V8 JavaScript engine, enabling the server-side development of scalable and high-performance applications.

- **Socket.IO:** A library that enables real-time, bidirectional, and event-based communication between the browser and the server.
