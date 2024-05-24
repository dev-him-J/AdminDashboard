# Admin Dashboard

This project is an Admin Dashboard built using React and TypeScript on the frontend, and Node.js with Express on the backend.

## Installation

### Prerequisites

Make sure you have the following software installed:

- Node.js
- npm or yarn

### Backend Setup

1. Clone the repository:

    ```sh
    git clone https://github.com/yourusername/admin-dashboard.git
    cd admin-dashboard/backend
    ```

2. Install backend dependencies:

    ```sh
    npm install
    # or
    yarn install
    ```

3. Set up environment variables:

    Create a `.env` file in the `backend` directory and add the following:

    ```env
    PORT=5000
    DATABASE_URL=your_database_url
    JWT_SECRET=your_jwt_secret
    ```

4. Start the backend server:

    ```sh
    npm run dev
    # or
    yarn dev
    ```

### Frontend Setup

1. Navigate to the frontend directory:

    ```sh
    cd ../frontend
    ```

2. Install frontend dependencies:

    ```sh
    npm install
    # or
    yarn install
    ```

3. Set up environment variables:

    Create a `.env` file in the `frontend` directory and add the following:

    ```env
    REACT_APP_API_URL=http://localhost:5000/api
    ```

4. Start the frontend development server:

    ```sh
    npm start
    # or
    yarn start
    ```

## Usage

- Visit `http://localhost:3000` in your browser to access the frontend.
- The backend API will be available at `http://localhost:5000/api`.
