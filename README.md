# PERN Todo List Application

This is a simple Todo List application built using the PERN stack (PostgreSQL, Express, React, Node.js).

## Features

- **Add, Edit, Update and Delete:** Manage your tasks effortlessly.
- **Mark as Complete/Incomplete:** Keep track of your progress.
<!-- - **Filter Tasks:** Easily sort tasks by their completion status. -->
- **Responsive Design:** Enjoy a seamless experience across devices.

## Technologies Used

- **Frontend:**
  - React with React Router for navigation
  - Axios for API requests
  <!-- - Bootstrap for a sleek UI -->

- **Backend:**
  - Node.js and Express.js for the server
  - PostgreSQL as the database
  - Sequelize ORM for handling database interactions

## Getting Started

### Prerequisites

- Node.js installed on your machine
- PostgreSQL installed and running locally

### Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/your-username/PERN-todolist.git
    ```

2. **Navigate to the project directory:**

    ```bash
    cd PERN-todolist
    ```

3. **Install dependencies:**

    ```bash
    # Backend dependencies
    cd server
    npm install

    # Frontend dependencies
    cd ../client
    npm install
    ```

4. **Set up the database:**

    - Create a PostgreSQL database named `database`.
    - Configure the database connection in `server/config/config.json`.

5. **Start the backend server:**

    ```bash
    # Backend server
    cd server
    npm start
    ```

6. **Start the frontend:**

    ```bash
    # Frontend app
    cd client
    npm start
    ```

7. **Access the app in your browser:** Go to `http://localhost:3000`.

## Folder Structure

- `/client`: Contains React frontend code
- `/server`: Holds Node.js backend code
  - `/server/config`: Database configuration files
  - `/server/models`: Sequelize models
  - `/server/routes`: Express route handlers
  - `/server/controllers`: Controllers for route handling
  - `/server/middleware`: Custom middleware

## Contributing

Feel free to contribute! Please open an issue for discussion or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
