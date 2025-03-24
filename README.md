Install Dependencies:
<br>

Open two separate Command Prompt windows:
<br>
In the first window:
<br>
bash
<br>
cd backend
<br>
npm install
<br>
In the second window:
<br>
bash
<br>
cd frontend
<br>
npm install
<br>
Configure Environment Variables:
<br>
<br>
Navigate to the backend folder and create a .env file.
<br>
Add the following:
<br>
PORT=5000
MONGO_URI=your-mongodb-connection-uri
JWT_SECRET=your-jwt-secret
<br>
Start MongoDB:
<br>
Ensure MongoDB server is running locally. Start it using the MongoDB Compass GUI or by running:
<br>
bash
<br>
mongod
<br>
(Make sure mongod.exe is in your PATH.)
<br>
<br>
Start the Backend Server:
<br>
<br>In the first Command Prompt window, run:
<br>
bash
<br>
npm start
<br>
Start the Frontend Server:

<br>
In the second Command Prompt window, run:

<br>bash

<br>
npm start
<br>
Access the Application:
