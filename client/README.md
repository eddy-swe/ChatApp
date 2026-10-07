# ChatApp Frontend

## Overview
This is the frontend for ChatApp, a real-time messaging application. The client provides a user-friendly interface for sending and receiving messages.

## Tech Stack
- **React** - UI library for building interactive components
- **JavaScript/ES6** - Programming language
- **Tailwind** - Styling
- **Axios** - HTTP client for API requests
- **Socket.io** - Real-time communication with the server

## Project Structure

```
client/
├── src/
│   ├── components/       # Reusable React components
│   ├── pages/           # Page components (Chat, Login, etc.)
│   ├── services/        # API and service calls
│   ├── styles/          # Global and component styles
│   ├── utils/           # Utility functions and helpers
│   ├── App.js           # Main App component
│   └── index.js         # React entry point
├── public/              # Static assets and HTML template
├── package.json         # Dependencies and scripts
└── README.md           # This file
```

## Getting Started

1. Install dependencies:
   ```bash
   npm install
   ```

2. Start the development server:
   ```bash
   npm start
   ```

3. Build for production:
   ```bash
   npm run build
   ```

## Key Features
- User authentication and login
- Real-time message sending and receiving
- Chat history
- User-friendly message interface