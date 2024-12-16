# Kanban Project

A full-stack Kanban board application with a modern frontend and robust backend architecture.

## Project Structure

The project is divided into two main components:
- `kanban-frontend`: React-based frontend application
- `kanban-backend`: Node.js backend application

## Prerequisites

- Docker and Docker Compose
- Node.js (for local development)
- npm or yarn package manager

## Quick Start with Docker

1. Clone the repository
2. Navigate to the project root directory
3. Run the following command:
```bash
docker-compose up
```

This will start both the frontend and backend services. The application will be available at:
- Frontend: http://localhost:3000
- Backend API: http://localhost:5000

## Manual Setup (Development)

### Backend Setup
1. Navigate to the backend directory:
```bash
cd kanban-backend
```

2. Install dependencies:
```bash
npm install
```

3. Start the backend server:
```bash
npm start
```

### Frontend Setup
1. Navigate to the frontend directory:
```bash
cd kanban-frontend
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm start
```

## Features

- Drag and drop interface for task management
- Multiple boards support
- Real-time updates
- Task categorization and prioritization
- User authentication and authorization
- Responsive design for mobile and desktop

## Architecture

The application follows a microservices architecture:

- Frontend: React.js application with modern state management
- Backend: Node.js API server
- Docker containers for easy deployment and scaling

