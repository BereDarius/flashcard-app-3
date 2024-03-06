# Flashcard App

This is a flashcard app built with a backend made in Nest.js with GraphQL, TypeORM, and Postgres, and a frontend made with Next.js and shadcn/ui.

## Installation

To run the flashcard app, you'll need to install the dependencies for both the backend and frontend.

### Backend

1. Navigate to the backend directory: `cd backend`
2. Install the dependencies: `yarn install`

### Frontend

1. Navigate to the frontend directory: `cd frontend`
2. Install the dependencies: `yarn install`

## Configuration

Before running the app, you'll need to configure the backend to connect to your Postgres database.

1. Open the `backend/.env` file.
2. Update the following variables with your Postgres database connection details:

- `POSTGRES_HOST`
- `POSTGRES_PORT`
- `POSTGRES_DB`
- `POSTGRES_USER`
- `POSTGRES_PASSWORD`
- `NODE_ENV`
- `PORT`
- `RUN_MIGRATIONS`

## Usage

To start the app, you'll need to start both the backend and frontend servers.

### Backend

1. Navigate to the backend directory: `cd backend`
2. Start the server: `yarn start:dev`

### Frontend

1. Navigate to the frontend directory: `cd frontend`
2. Start the server: `yarn dev`

## License

This project is licensed under the [MIT License](LICENSE).
