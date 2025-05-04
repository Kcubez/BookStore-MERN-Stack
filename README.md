# MERN Stack Bookstore Application

A full-stack web application for managing a bookstore, built with the MERN stack (MongoDB, Express.js, React.js, Node.js).

## Features

- Create, Read, Update, and Delete (CRUD) operations for books
- RESTful API architecture
- Modern and responsive user interface
- Real-time data updates
- Form validation
- Error handling

## Tech Stack

### Backend
- Node.js
- Express.js
- MongoDB with Mongoose
- CORS for cross-origin requests

### Frontend
- React.js
- Vite
- React Router for navigation
- Axios for API requests
- TailwindCSS for styling
- React Icons
- Notistack for notifications

## Prerequisites

Before running this project, make sure you have the following installed:
- Node.js (v14 or higher)
- MongoDB
- npm or yarn

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd BookStore-MERN-Stack
```

2. Install backend dependencies:
```bash
cd backend
npm install
```

3. Install frontend dependencies:
```bash
cd ../frontend
npm install
```

## Configuration

1. Create a `.env` file in the backend directory with the following variables:
```
PORT=5000
MONGODB_URI=your_mongodb_connection_string
```

## Running the Application

1. Start the backend server:
```bash
cd backend
npm run dev
```

2. Start the frontend development server:
```bash
cd frontend
npm run dev
```

The application will be available at:
- Frontend: http://localhost:5173
- Backend API: http://localhost:5000

## API Endpoints

### Books
- `GET /api/books` - Get all books
- `GET /api/books/:id` - Get a specific book
- `POST /api/books` - Create a new book
- `PUT /api/books/:id` - Update a book
- `DELETE /api/books/:id` - Delete a book

## Project Structure

```
BookStore-MERN-Stack/
├── backend/
│   ├── models/
│   ├── routes/
│   ├── index.js
│   └── package.json
├── frontend/
│   ├── src/
│   ├── public/
│   └── package.json
└── README.md
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the ISC License.

## Contact

Kaung Khant Kyaw - kcubez21@gmail.com

Project Link: [https://github.com/kcubez/BookStore-MERN-Stack](https://github.com/kcubez/BookStore-MERN-Stack)
