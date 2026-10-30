# React + Vite

## Backend API

The frontend sends conversions to `VITE_API_URL`. For local development it
defaults to `http://localhost:3000`. Set `VITE_API_URL` in the frontend's Vercel
project to the deployed backend URL (for example, `https://your-backend.vercel.app`)
and redeploy the frontend.

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
