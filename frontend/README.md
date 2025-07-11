# Frontend Application (React with TypeScript)

This directory contains the frontend application for the Expense Tracker, built with React, TypeScript, and Vite.

## Technologies Used

*   **Framework**: React 18.2
*   **Language**: TypeScript 5.3
*   **Build Tool**: Vite 5.x
*   **API Client**: Axios (to be installed)
*   **State Management**: React Context API (or Zustand if needed)
*   **Styling**: Tailwind CSS or Styled Components (to be decided)

## Setup and Installation

To set up and run the frontend application locally, follow these steps:

1.  **Navigate to the frontend directory**:
    ```bash
    cd frontend
    ```

2.  **Install dependencies**:
    Ensure you have Node.js (v18 or higher recommended) and npm/yarn/pnpm installed.
    ```bash
    npm install   # or yarn install or pnpm install
    ```

3.  **Start the development server**:
    ```bash
    npm run dev   # or yarn dev or pnpm dev
    ```
    The application will typically be available at `http://localhost:5173`.

4.  **Build for production**:
    ```bash
    npm run build   # or yarn build or pnpm build
    ```
    This will create a `dist/` directory with the production-ready static assets.

## Project Structure

```
frontend/
├── public/
│   └── vite.svg           # Public assets
├── src/
│   ├── assets/            # Static assets like images (optional)
│   ├── components/        # Reusable UI components
│   ├── pages/             # Page-level components
│   ├── services/          # API integration logic (e.g., axios instances)
│   ├── hooks/             # Custom React hooks
│   ├── contexts/          # React Context API providers (for global state)
│   ├── types/             # TypeScript type definitions
│   ├── App.css            # Global CSS for App component
│   ├── App.tsx            # Main application component
│   ├── index.css          # Global CSS styles
│   └── main.tsx           # Entry point for the React application
├── index.html             # Main HTML file
├── package.json           # Project dependencies and scripts
├── tsconfig.json          # TypeScript configuration
├── vite-env.d.ts          # Vite environment type definitions
├── vite.config.ts         # Vite build configuration
└── README.md              # This file
```

## Available Scripts

*   `npm run dev`: Starts the development server with hot-reloading.
*   `npm run build`: Builds the app for production to the `dist` folder.
*   `npm run lint`: Lints the code for potential errors and style issues.
*   `npm run preview`: Serves the `dist` folder locally for previewing the production build.

## API Integration

The frontend will interact with the backend API (Django REST Framework) via RESTful endpoints. Axios will be used for making HTTP requests.
Ensure the backend server is running and accessible. The API base URL will be configured in the environment variables (e.g., `.env.development`, `.env.production`).

## Styling

(Decision pending between Tailwind CSS or Styled Components. Once decided, instructions will be updated here.)

## Contributing

Please refer to the overall project's `CONTRIBUTING.md` (if available) for contribution guidelines.
