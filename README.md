To-Do List App
This is a full-stack To-Do List application with a React frontend and a Node.js + Express + MongoDB backend. Users can add, update, delete, and manage tasks in real-time.

Setup and Run Locally
Backend
Navigate to the backend folder:
cd todo-backend
Install dependencies:
npm install
Create environment variables:
Rename .env.example to .env
Add your MongoDB connection string:
MONGO_URI=<Your-MongoDB-URI>
Start the backend server:
npm start
The backend will run on the port specified in your server code or process.env.PORT.
Frontend
Navigate to the frontend folder:
cd todo-frontend
Install dependencies:
npm install
Create environment variables:
Rename .env.example to .env
Add your backend URL:
VITE_BACKEND_URL=http://localhost:5000
Run the frontend development server:
npm run dev
Open http://localhost:5173 in your browser.
To build for production:
npm run build
A dist folder will be created for deployment.

Deployment
Frontend: Upload the dist folder to Netlify.
Backend: Deploy the Node.js API to Render.
Update the frontend .env file with the deployed backend URL.

Challenges and Solutions
Frontend-backend integration: Ensured correct API URLs were used through environment variables.
State management: Used React useState to handle tasks efficiently.
Error handling: Displayed meaningful messages when API requests failed to improve UX.
Deployment issues: Configured start script and PORT in backend to work on Render.



