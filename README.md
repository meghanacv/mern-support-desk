# Support Ticket App
Support Ticket App is a full-stack web application developed with the MERN (MongoDB, Express.js, React.js, Node.js) stack. It serves as a platform for managing support tickets, facilitating communication between users and support teams.

### Technologies Used
- MongoDB Atlas: Cloud-based MongoDB database service.
- MongoDB Compass: GUI tool for interacting with MongoDB databases.
- Express.js: Node.js web application framework for building APIs.
- React.js: JavaScript library for building user interfaces.
- Node.js: JavaScript runtime environment for server-side development.
- Redux Toolkit: Redux library for state management.
- Postman: API development tool for testing and debugging.

### Environment Variables
Ensure you have an .env file in the root directory of your project with the following variables:

NODE_ENV=development
PORT=5000
MONGO_URI=mongodb+srv://youruri
JWT_SECRET=<your_secret_key>
Replace youruri with your MongoDB connection URI and <your_secret_key> with your desired secret key for JWT authentication.

#### Installation
To install backend dependencies, run 
`npm install`

To install client dependencies, navigate to the frontend directory and run:

`cd frontend
npm install`

#### Running the Application
To run both the backend and frontend concurrently, use:

`npm run dev`
This command will start the server at **http://localhost:5000** and the client at **http://localhost:3000**.
