# React Vite Boilerplate

This project is a boilerplate for building React applications using Vite. It provides a fast and efficient development environment with a focus on performance and best practices.

## Features

- **Vite**: Next-generation frontend tooling for fast builds and hot module replacement.
- **React**: A JavaScript library for building user interfaces.
- **TypeScript**: Static type checking to improve code quality and developer experience.
- **Tailwind CSS**: A utility-first CSS framework for rapid UI development.
- **Zustand**: A small, fast, and scalable state management library for React.
- **TanStack Query**: Powerful asynchronous state management for data fetching, caching, and updating.
- **Axios**: A promise-based HTTP client for making API requests.
- **ESLint**: Pluggable linting tool for identifying and reporting on patterns in JavaScript.
- **Prettier**: An opinionated code formatter to ensure consistent code style.
- **Husky**: Git hooks made easy, enabling pre-commit and pre-push hooks.
- **Commitlint**: Lints commit messages to ensure they follow conventional commit standards.

## Getting Started

Follow these steps to set up and run the project locally.

### Prerequisites

- Node.js (version 14 or higher)
- npm or yarn package manager

### Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/crljhnmngs/react-vite-boilerplate.git
    cd react-vite-boilerplate
    ```

2. **Install dependencies:**

    Using npm:

    ```bash
    npm install
    ```

    Or using yarn:

    ```bash
    yarn install
    ```

### Running the Development Server

To start the development server with hot module replacement:

```bash
npm run dev
```

Or with yarn:

```bash
yarn dev
```

The application will be available at `http://localhost:3000`.

### Building for Production

To create an optimized production build:

```bash
npm run build
```

Or with yarn:

```bash
yarn build
```

The output will be in the `dist` directory.

### Previewing the Production Build

To preview the production build locally:

```bash
npm run preview
```

Or with yarn:

```bash
yarn preview
```

This will start a local server to serve the production build.

The project's file structure is organized as follows:

```
react-vite-boilerplate/
├── .husky/                 # Husky configuration for Git hooks
├── src/                    # Source code
│   ├── assets/             # Static assets (images, fonts, etc.)
│   ├── components/         # Reusable React components
│   ├── hooks/              # Custom hooks (e.g., Zustand and TanStack Query)
│   ├── pages/              # React components for pages
│   ├── store/              # Zustand state management
│   ├── services/           # Axios API services
│   ├── App.tsx             # Main application component
│   └── main.tsx            # Entry point for React
├── .env                    # Environment variables
├── .gitignore              # Git ignore file
├── .prettierrc             # Prettier configuration
├── commitlint.config.ts    # Commitlint configuration
├── eslint.config.js        # ESLint configuration
├── index.html              # Main HTML file
├── package.json            # Project metadata and scripts
├── tailwind.config.cjs     # Tailwind CSS configuration
├── tsconfig.json           # TypeScript configuration
└── vite.config.ts          # Vite configuration
```

## Available Scripts

- `dev`: Starts the development server.
- `build`: Builds the app for production.
- `preview`: Previews the production build locally.
- `lint`: Runs ESLint to analyze code for potential errors.
- `format`: Formats code using Prettier.
