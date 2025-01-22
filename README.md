Installation and Setup

Ensure the following are installed on your system:
   . Node.js (v16 or above)
   . MongoDB (local or cloud instance)
   . npm or yarn

Backend Setup 

   1. Navigate to the backend folder:  $ cd backend
   2. Install dependencies: $ npm install
   3. Create a .env file and configure the following:
        . MONGO_URI = your_mongodb_connection_string
        . JWT_SECRET = your_jwt_secret_key
        . PORT=3000
   4. Start the backend server: $ npm start
      
Frontend Setup

   1. Navigate to the frontend folder: $ cd frontend
   2. Install dependencies: $ npm install
   3. Start the React development server: $ npm start
