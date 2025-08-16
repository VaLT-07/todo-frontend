To-Do List App (Frontend)

This is the React frontend for the To-Do List application, integrated with a Node.js + Express.js + MongoDB backend. The app allows users to create, update, delete, search, and manage tasks in a user-friendly interface.

🔗 Live Demo

Frontend is deployed on Netlify:[Your Netlify URL here]

Backend APIs are deployed on Render:[Your Backend URL here]

⚙️ Features

Add new tasks

Update task details

Delete tasks

Mark tasks as complete/incomplete

Search tasks dynamically

Dynamic UI updates with real-time API responses

Error handling and loading indicators

🛠 Installation (Local Setup)

Clone the repository

git clone https://github.com/<YOUR-USERNAME>/<REPO>.git

Navigate to the project folder

cd todo-frontend

Install dependencies

npm install

Create environment variables

Rename .env.example to .env

Add your backend API URL:

VITE_BACKEND_URL=https://your-backend-url.onrender.com

Run the app locally

npm run dev

Open http://localhost:5173 in your browser.

Build for production

npm run build

This creates a dist folder for deployment.

📝 Project Structure

todo-frontend/
│
├─ src/                 # React components & styles
├─ public/              # Static files
├─ package.json         # Project metadata & dependencies
├─ vite.config.js       # Vite configuration
├─ .env.example         # Example environment variables
└─ README.md            # Project documentation

⚡ Deployment

Frontend: Netlify (manual upload of dist folder)

Backend: Render (Node.js + Express API)

⚠️ Notes / Challenges

Ensured real-time UI updates after API actions.

Implemented error handling for failed API requests.

Used .env to manage environment variables and switch between local and deployed backend.

