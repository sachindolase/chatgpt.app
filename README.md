# ChatGPT Realtime Chat Application

Welcome to the ChatGPT Realtime Chat Application repository! This project was developed by a team of four employee: Yogesh Baghel, Vikas Kumar Singh, Jatin Jadhav, and Sachin Dolase.

## About

The ChatGPT Realtime Chat Application is a full-stack web application that allows users to engage in real-time conversations with both human counterparts and an AI agent powered by OpenAI's GPT-3 model. The application leverages modern web technologies such as React, Node.js, and Chat Engine to provide a seamless and interactive chatting experience.

## Features

- Real-time chat functionality
- Integration with OpenAI's GPT-3 model for AI-assisted conversations
- User authentication and authorization
- Secure communication using HTTPS
- Responsive design for optimal user experience on various devices

## Getting Started

To get started with the ChatGPT Realtime Chat Application, follow these steps:

1. Clone the repository to your local machine:

```bash
git clone 
```

2. Install dependencies for both the frontend and backend:

```bash
cd chatgpt-realtime-chat-application
cd client && npm install
cd ../server && npm install
```

3. Set up environment variables:

   - Create a `.env` file in the `server` directory.
   - Define the following environment variables in the `.env` file:

   ```plaintext
   PORT=9000
   OPEN_API_KEY=your_openai_api_key
   ```

4. Start the development servers:

```bash
# Start the backend server
cd server && npm start

# Start the frontend server
cd ../client && npm start
```

5. Access the application in your web browser at `http://localhost:3000`.

> Thank you...

