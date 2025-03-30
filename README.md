# Expensify - Expense Management System (Frontend)

Expensify is a modern expense management system designed to help users track their income and expenses efficiently. This repository contains the frontend code for the application, built using React and Vite.

## Table of Contents

- [Expensify - Expense Management System (Frontend)](#expensify---expense-management-system-frontend)
  - [Table of Contents](#table-of-contents)
  - [Features](#features)
  - [Tech Stack](#tech-stack)
  - [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
    - [Running Locally](#running-locally)
  - [Project Structure](#project-structure)
  - [Scripts](#scripts)
  - [Contributing](#contributing)
  - [Acknowledgments](#acknowledgments)

---

## Features

- User authentication (Login/Register)
- Add, edit, and delete transactions
- Filter transactions by date, type, and category
- View analytics for income and expenses
- Responsive design with Bootstrap and Ant Design
- Protected routes for authenticated users

---

## Tech Stack

- **Frontend Framework**: React (with React Router)
- **Build Tool**: Vite
- **UI Libraries**: Ant Design, Bootstrap
- **State Management**: React Hooks
- **HTTP Client**: Axios
- **Date Handling**: Moment.js
- **Linting**: ESLint

---

## Getting Started

### Prerequisites

Ensure you have the following installed on your system:

- [Node.js](https://nodejs.org/) (v16 or higher)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Shashikr36/expensify-frontend.git
   cd expensify-frontend
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

### Running Locally

1. Start the development server:

   ```bash
   npm run dev
   ```

2. Open your browser and navigate to `http://localhost:5173`.

---

## Project Structure

```
Expensify-Frontend/
├── public/                # Static assets
├── src/
│   ├── components/        # Reusable components (e.g., Header, Footer, Analytics)
│   ├── pages/             # Page components (e.g., HomePage, Login, Register)
│   ├── App.jsx            # Main application component
│   ├── main.jsx           # Entry point
│   ├── index.css          # Global styles
│   └── App.css            # Component-specific styles
├── .eslintrc.cjs          # ESLint configuration
├── vite.config.js         # Vite configuration
├── package.json           # Project metadata and dependencies
└── README.md              # Project documentation
```

---

## Scripts

The following scripts are available in the project:

- `npm run dev`: Start the development server.
- `npm run build`: Build the project for production.
- `npm run preview`: Preview the production build.
- `npm run lint`: Run ESLint to check for code quality issues.

---

## Contributing

Contributions are welcome! If you'd like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature-name`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/your-feature-name`).
5. Open a pull request.

---

## Acknowledgments

- [React](https://reactjs.org/)
- [Vite](https://vitejs.dev/)
- [Ant Design](https://ant.design/)
- [Bootstrap](https://getbootstrap.com/)
- [Moment.js](https://momentjs.com/)