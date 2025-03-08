# Bookstore Project

This is a full-stack MERN (MongoDB, Express, React, Node.js) bookstore application. It provides a simple interface for managing a collection of books, including creating, editing, deleting, and viewing book details.

## Prerequisites

To run this project, you need to have the following installed:

- Node.js
- npm (Node Package Manager)
- MongoDB

## Installation

1. Clone the repository:

   ```bash
   git clone <repository_url>
   cd bookstore-project
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

## Running the Application

1. Start the MongoDB server.

2. Run the backend server:

   ```bash
   cd backend
   npm run dev
   ```

   This will start the backend server on `http://localhost:5555`.

3. Run the frontend development server:

   ```bash
   cd ../frontend
   npm run dev
   ```

   This will start the frontend server on `http://localhost:3000`.

4. Open your browser and navigate to `http://localhost:3000` to view the application.

## Project Structure

- **backend/**: Contains the Express server code and MongoDB models.
- **frontend/**: Contains the React application code.

## Key Features

- Add a new book with title, author, and publish year.
- Edit existing book details.
- Delete a book from the collection.
- View a list of all books.
- View detailed information about a single book.

## Dependencies

### Backend

- express
- mongoose
- dotenv
- cors
- nodemon (for development)

### Frontend

- react
- react-dom
- react-router-dom
- axios
- notistack
- react-icons
- tailwindcss

## Environment Variables

Create a `.env` file in the `backend` directory and add the following:

```plaintext
PORT=5555
MONGO_URL=<your_mongodb_connection_string>
```

Replace `<your_mongodb_connection_string>` with your MongoDB connection string.

## License

This project is licensed under the ISC License.
