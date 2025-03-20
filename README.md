# Claims Processing System

A modern claims processing application with a React frontend and Express.js backend.

## Project Structure

This project follows a client-server architecture:

- `/claims-management-system/client`: React frontend application
- `/claims-management-system/server`: Express.js backend API

## Setup Instructions

### Prerequisites

- Node.js (v16 or higher)
- npm (v8 or higher)

### Installation

1. Clone the repository
2. Install dependencies:
   ```
   npm install
   ```

### Development

To run both client and server in development mode:

```
npm run dev
```

This will start:
- The React client on http://localhost:5173 (or another port if 5173 is in use)
- The Express server on http://localhost:4000

### Building for Production

```
npm run build
```

### Running in Production

```
npm start
```

## Features

- Claims submission and management
- User authentication and authorization
- File attachments and document management
- Reporting and analytics
- Email notifications
