To-Do List App

This is a simple **To-Do List application** with a React frontend integrated with a Node.js + Express + MongoDB backend. Users can add, update, delete, and manage tasks in real-time.

---

## Setup and Run Locally

1. **Clone the repository**

```bash
git clone https://github.com/VaLT-07/todo-frontend
```

2. **Go to the frontend folder**

```bash
cd todo-frontend
```

3. **Install dependencies**

```bash
npm install
```


5. **Run the app locally**

```bash
npm run dev
```

- Open `http://localhost:5173` in your browser.

6. **Build for production**

```bash
npm run build
```

- A `dist` folder will be created for deployment.

---

## Deployment

- Frontend: Upload the `dist` folder to **Netlify**.
- Backend: Deploy the Node.js API to **Render** or any hosting service.

---

## Challenges and Solutions

- **Integrating frontend with backend:** Ensured API calls used the correct deployed backend URL through `.env`.
- **Real-time updates:** Used React state management (`useState`) to update UI immediately after API calls.
- **Error handling:** Implemented messages for failed API requests to improve user experience.

---

## Decisions Made During Enhancement

- Chose **React** with functional components and hooks for a modern and maintainable frontend.
- Used **Vite** as the build tool for faster development and simpler configuration.
- Implemented **state management using **`` to handle task data efficiently.
- Organized code into **components** for modularity and readability.
- Used **.env file** to manage environment variables and switch easily between local and deployed backends.
- Added **loading indicators and error messages** to improve user experience.





## Author

- VaLT
