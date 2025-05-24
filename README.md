A real-time chat application built with the MERN stack (MongoDB, Express, React, Node.js), featuring Zustand for state management, Axios for API calls, and React Router for navigation.
This app allows users to send and receive messages in real-time.

## Live Demo

You can try the live version of the app here: [Live Chat App](https://chat-app-mern-fullstack.onrender.com/)




Features
Real-time Messaging: Users can send and receive messages instantly.
User Authentication: Secure login and registration using JWT tokens.
Responsive Design: Fully responsive layout optimized for mobile and desktop devices.
State Management: Global state management using Zustand to handle user sessions and messages.
Routing: Seamless navigation between different pages using React Router.
API Integration: Axios is used for making requests to the backend API for messaging and user management.



Technologies Used
Frontend:
React: A JavaScript library for building user interfaces.
React Router: For handling routing between different views.
Zustand: A state management tool for global state in React.
Axios: To make API requests to the backend.
CSS/Tailwind: For styling the app (or your choice of CSS framework).


Backend:
Node.js: JavaScript runtime used for the backend server.
Express: Web framework for building RESTful APIs.
MongoDB: Database to store user data and chat messages.
JWT: JSON Web Tokens for authentication.


#Project Structure

├── backend/
│ ├── controllers/
│ │ ├── authController.js
│ │ └── messageController.js
│ ├── models/
│ │ ├── User.js
│ │ └── Message.js
│ ├── routes/
│ │ ├── authRoutes.js
│ │ └── messageRoutes.js
│ ├── server.js
│ └── .env
└── frontend/
├── src/
│ ├── components/
│ │ ├── Chat.js
│ │ ├── Login.js
│ │ └── Register.js
│ ├── context/
│ │ └── ChatContext.js
│ ├── App.js
│ ├── index.js
│ └── tailwind.config.js
└── public/
└── index.html


## Getting Started

### Prerequisites

- Node.js
- MongoDB
- npm or yarn

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/ishan228/Chat-App-MERN-FullStack.git
   cd Chat-App-MERN-FullStack

2. Install Dependencies
   cd backend
  npm install

3. Set up Environment Variable
   MONGO_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret

4. Start the backend Server
   npm start
6. Install frontend Dependencies
   cd ../frontend
   npm install
8. Start the frontend development Server
   npm start
   The application will be available at http://localhost:3000.


Usage
Register: Create a new account by providing a username and password.

Login: Access your account using your credentials.

Chat: Send and receive messages in real-time with other users.

Contributing
Contributions are welcome! If you have suggestions for improvements or new features, feel free to open an issue or submit a pull request.

License
This project is licensed under the MIT License.

