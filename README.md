# React + Vite

# OTT Platform - React App

This is a **React.js** project built using:
- React 18
- React Router
- Axios
- Vite
- JSON Server (for backend)
Project Overview
OTT App is a dynamic web application that delivers an immersive streaming experience. Built with React and powered by FakeJSON, it efficiently manages user interactions, content fetching, and state management.


Key Features
- Global State Management: Utilized Redux Toolkit to manage application-wide state, ensuring seamless data flow across components.

- Context API for Theming: Integrated Context API to manage UI themes and user preferences efficiently.

- Asynchronous Data Fetching: Implemented async/await with API calls to FakeJSON, ensuring real-time content updates.

- Optimized Performance: Used React.memo and lazy loading for enhanced performance.

Tech Stack
- Frontend: React (Vite)

- State Management: Redux Toolkit, Context API

- Async Handling: Fetch API, Axios

- Backend (Mocked): FakeJSON




To run the project:
```sh
npm install
npm run dev(to start frontend)
json-server --watch db.json --port 5000(to starat backend (fakejson))

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh



