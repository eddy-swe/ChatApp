# ChatApp Server

Backend server for the ChatApp application.

## Tech Stack

- **Runtime**: Node.js
- **Framework**: Express.js
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Tokens)
- **Real-time Communication**: Socket.io
- **Environment Management**: dotenv

## Project Structure

```
server/
├── config/              # Configuration files
├── controllers/         # Request handlers
├── models/             # Database schemas
├── routes/             # API routes
├── middleware/         # Custom middleware
├── utils/              # Utility functions
├── socket/             # Socket.io handlers
├── .env.example        # Environment variables template
├── .gitignore          # Git ignore file
├── package.json        # Dependencies
└── server.js           # Entry point
```

## Installation

1. Install dependencies:
```bash
npm install
```

2. Create `.env` file from `.env.example` and configure:
```bash
cp .env.example .env
```

3. Start the server:
```bash
npm start
```

## API Endpoints

- **Auth**: `/api/auth/*` - User authentication
- **Messages**: `/api/messages/*` - Message operations
- **Users**: `/api/users/*` - User management
- **Rooms**: `/api/rooms/*` - Chat rooms management

## Real-time Events

Socket.io events for live messaging and notifications:
- `connect` - User connects
- `message` - New message
- `typing` - User typing indicator
- `disconnect` - User disconnects

## Environment Variables

Required in `.env`:
- `PORT` - Server port
- `MONGODB_URI` - Database connection string
- `JWT_SECRET` - JWT signing secret
- `NODE_ENV` - Environment (development/production)

## Running Tests

```bash
npm test
```

## License

Proprietary - ChatApp Project
