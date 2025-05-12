Welcome to Mind Canvas, a full-stack MERN (MongoDB, Express, React, Node.js) web application inspired by Twitter. This project is a clone-style memory sharing platform where users can post, update, and delete "memories" — thoughts, moments, or ideas — just like tweeting.

📍 Repository: project_mern_memories-PART_1_and_2

🚀 Features
🔐 User Authentication with JWT and Google OAuth

📄 CRUD operations on posts (Create, Read, Update, Delete)

🧵 Like & comment functionality

📸 Image upload support using base64 encoding

🔍 Search memories by title or tags

🧰 Fully functional RESTful backend with Express

🎨 Responsive React UI with Material-UI components

🛠️ Tech Stack
Frontend: React, Redux, Material-UI

Backend: Node.js, Express.js

Database: MongoDB Atlas

Authentication: JSON Web Tokens (JWT), Google OAuth 2.0

📂 Project Structure
bash
Copy
Edit
project_mern_memories-PART_1_and_2/
│
├── client/             # React frontend
│   ├── components/     # Reusable UI components
│   ├── pages/          # Main pages (Home, Auth, etc.)
│   └── ...
│
├── server/             # Express backend
│   ├── controllers/    # Route logic
│   ├── models/         # MongoDB schemas
│   ├── routes/         # API endpoints
│   └── ...
🧪 Getting Started
Clone the repository

bash
Copy
Edit
git clone https://github.com/Aditya-Kashyap04/Mind-Canvas-like-twitter.git
cd Mind-Canvas-like-twitter/project_mern_memories-PART_1_and_2
Install dependencies

bash
Copy
Edit
cd client
npm install
cd ../server
npm install
Set up environment variables

Create a .env file in the server directory and add:

ini
Copy
Edit
PORT=5000
MONGO_URI=your_mongo_connection_string
JWT_SECRET=your_jwt_secret
GOOGLE_CLIENT_ID=your_google_client_id
Run the application

Start backend: npm start from /server

Start frontend: npm start from /client

📸 Screenshots
(Optional section: Include screenshots or a demo video link if available.)

🙌 Acknowledgements
This project is based on the JavaScript Mastery MERN Memories tutorial with custom features and enhancements added.
