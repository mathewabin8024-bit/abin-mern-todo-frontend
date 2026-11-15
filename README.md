# Daymark Frontend

This is the standalone React/Vite frontend for Abin Mathew's Todo app. The backend remains deployed on Render at `https://abin-mern-todo.onrender.com`.

## Deploy on Vercel

1. Create a separate GitHub repository named `abin-mern-todo-frontend` and push the contents of this folder to its root.
2. In Vercel, import that repository. Vercel will use `vercel.json` to build the Vite app.
3. Add the environment variable `VITE_API_URL` with the value `https://abin-mern-todo.onrender.com`.
4. Deploy and copy the resulting Vercel URL.
5. In Render, set `CLIENT_ORIGINS` to the new Vercel URL, save and redeploy the backend.

The frontend URL and backend URL will then be separate. The backend root also continues to serve the app as required by the assignment.

## Local development

Set `VITE_API_URL=http://localhost:5000` in a local `.env.local`, install dependencies with `npm install`, then run `npm run dev`.
