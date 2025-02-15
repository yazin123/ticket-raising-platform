# Ticket Raising Platform

A comprehensive ticket management system built with the MERN stack (MongoDB, Express.js, React.js, Node.js). This application allows users to create, manage, and track tickets for various issues or tasks.

## Features

- Create tickets with title, description, creator details, and priority level
- Update ticket status and details
- Delete tickets
- Filter tickets by status and priority
- Search functionality
- Real-time updates
- Responsive design

## Tech Stack

- **Frontend**: React.js, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **API**: RESTful API

## Prerequisites

Before you begin, ensure you have the following installed:
- Node.js (v14 or higher)
- MongoDB
- npm or yarn

## Installation

1. Clone the repository
```bash
git clone https://github.com/yazin123/ticket-raising-platform.git
cd ticket-raising-platform
```

2. Install backend dependencies
```bash
cd backend
npm install
```

3. Install frontend dependencies
```bash
cd ../frontend
npm install
```

4. Create a .env file in the backend directory with the following variables:
```env
MONGODB_URI=mongodb://localhost:27017/ticket-platform
PORT=5000
```

## Running the Application

1. Start the backend server
```bash
cd backend
npm start
```

2. Start the frontend development server
```bash
cd frontend
npm start
```

The application will be available at `http://localhost:3000`

## API Endpoints

- `GET /api/tickets` - Get all tickets
- `POST /api/tickets` - Create a new ticket
- `PUT /api/tickets/:id` - Update a ticket
- `DELETE /api/tickets/:id` - Delete a ticket

## Project Structure

```
ticket-raising-platform/
├── backend/
│   ├── server.js
│   ├── package.json
│   └── ...
└── frontend/
    ├── src/
    │   ├── components/
    │   ├── services/
    │   └── ...
    ├── package.json
    └── ...
```

## Features in Detail

### Ticket Creation
- Title
- Description
- Creator information
- Priority level (Low, Medium, High)
- Status tracking

### Ticket Management
- Update ticket status
- Modify ticket details
- Delete tickets
- Priority level adjustment

### Filtering and Search
- Filter by status
- Filter by priority
- Search across all ticket fields

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details
