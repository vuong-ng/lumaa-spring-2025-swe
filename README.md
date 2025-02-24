# Full-Stack Coding Challenge

**Deadline**: Sunday, Feb 23th 11:59 pm PST

---

# Task Management App

## Setup Instructions

### 1. Database Setup

#### Prerequisites
- PostgreSQL installed
- Node.js and npm installed

#### Steps to Set Up Database
1. **Create a `.env` file** in the root directory and add the following environment variables:
   ```env
  PORT=3000
  DB_USER='postgres'
  DB_PASSWORD='@Vuong10072003'
  DB_NAME = 'lumaatasks'
   ````


### 2. Running the Backend
1. Navigate to the backend directory:
   ```sh
   cd server
   ```
   
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the server:
   ```sh
   node index 
   npx nodemon index
   ```

### 3. Running the Frontend
1. Navigate to the frontend directory:
   ```sh
   cd frontend
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the React application:
   ```sh
   npm run dev
   ```

## Testing
- Ensure your `.env` file is set up correctly.
- Run backend tests:
  ```sh
  npm test
  ```
- Run frontend tests:
  ```sh
  npm run test
  ```

## Video Demo
([Click here to view the demo](https://imgur.com/a/gM6kZUa))

### The demo includes:
- Registering a user
- Logging in
- Creating, updating, and deleting tasks

Good luck, and we look forward to your submission!
