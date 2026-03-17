# Customer Management System - Frontend

This is the React-based frontend for the Customer Management System.

## Tech Stack

- **Framework**: [Vite 8](https://vitejs.dev/) + [React 19](https://react.dev/)
- **Language**: JavaScript (ES6+)
- **UI Component Library**: [Ant Design 6 (antd)](https://ant.design/)
- **State Management/Data Fetching**: Axios / Fetch API
- **Styling**: Vanilla CSS / Ant Design Tokens

---

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18.x or higher recommended)
- [npm](https://www.npmjs.com/) (comes with Node.js)

### Installation

1. Navigate to the frontend directory:
   ```bash
   cd frontend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

### Development

To start the development server:

```bash
npm run dev
```

The application will be available at [http://localhost:5173](http://localhost:5173) (default Vite port).

---

## Features

- **Customer List**: View customers with server-side pagination, searching, and sorting.
- **Customer Management**: Create, Edit, and Delete customers.
- **Form Validation**: Integration with Ant Design Form for robust client-side validation.

---

## Integration with Backend

The Frontend is live at: `https://pbtask.abdullahkhan.net/`

The frontend is configured to communicate with the Backend API (Live: `https://productbox.runasp.net/api`).

To change the API URL, update the base configuration in your API service utility (e.g., `src/API/axios.js`).

---

## Available Scripts

In the project directory, you can run:

### `npm run dev`
Runs the app in development mode using Vite.

### `npm run build`
Builds the app for production to the `dist` folder.
