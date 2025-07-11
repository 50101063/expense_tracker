# Frontend Application

This is the frontend for the Expense Tracker web application, built with React, TypeScript, and Vite.

## Technologies Used

*   **Framework:** React 18.2
*   **Language:** TypeScript 5.3
*   **Build Tool:** Vite 5.x
*   **API Client:** Axios
*   **Styling:** (To be decided, e.g., Tailwind CSS or Styled Components)

## Setup and Execution Instructions

Follow these steps to set up and run the frontend application locally:

### Prerequisites

*   Node.js (version 18 or higher recommended)
*   npm or Yarn (npm is used in these instructions)

### 1. Navigate to the Frontend Directory

Open your terminal or command prompt and navigate to this `frontend` directory:

```bash
cd frontend
```

### 2. Install Dependencies

Install the necessary Node.js packages:

```bash
npm install
# or if you use yarn:
# yarn install
```

### 3. Run the Development Server

Start the development server. This will typically open the application in your default web browser at `http://localhost:5173` (or another available port).

```bash
npm run dev
# or if you use yarn:
# yarn dev
```

The application will automatically reload as you make changes to the source code.

### 4. Build for Production (Optional)

To create a production-ready build of the application:

```bash
npm run build
# or if you use yarn:
# yarn build
```

This will generate optimized static assets in the `dist/` directory, which can then be deployed to a static hosting service (e.g., AWS S3).

### 5. Preview Production Build (Optional)

To preview the production build locally:

```bash
npm run preview
# or if you use yarn:
# yarn preview
```

### Project Structure

```
frontend/
├── public/                     # Static assets (e.g., favicon)
├── src/
│   ├── assets/                 # Images, icons, etc.
│   ├── components/             # Reusable UI components
│   ├── pages/                  # Top-level page components (e.g., Dashboard, MonthlyExpenses)
│   ├── services/               # API interaction logic (e.g., axios instances, API calls)
│   ├── hooks/                  # Custom React hooks
│   ├── contexts/               # React Context API providers
│   ├── types/                  # TypeScript type definitions
│   ├── App.css                 # Global CSS for App component
│   ├── App.tsx                 # Main application component
│   ├── index.css               # Global styles
│   └── main.tsx                # Entry point for the React application
├── index.html                  # Main HTML file
├── package.json                # Project dependencies and scripts
├── tsconfig.json               # TypeScript configuration for the project
├── tsconfig.node.json          # TypeScript configuration for Node.js environment (Vite)
├── vite.config.ts              # Vite build tool configuration
└── README.md                   # This file
```

## API Integration

The frontend will communicate with the backend API (Django REST Framework) using Axios. Ensure the backend server is running and accessible. API endpoints will typically be configured in `src/services/api.ts` or similar.

## Contributing

Please refer to the overall project's `CONTRIBUTING.md` (if available) for guidelines on contributing to this project.
