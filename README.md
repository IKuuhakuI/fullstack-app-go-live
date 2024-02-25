# Fullstack Go Live Project

This project is based on the Fullstack Go Live App originally created by [FrancescoXX](https://github.com/FrancescoXX/go-fullstack-app) for educational purposes.

**Disclaimer**: This project is a study and adaptation of the original Fullstack Go Live App created by FrancescoXX. It is not intended for production use and may contain experimental or incomplete features.

## Overview

This project demonstrates the implementation of a full-stack web application, comprising a backend API built with Go (Golang) and a frontend user interface built with NextJS. The backend provides RESTful API endpoints to interact with a PostgreSQL database, and the frontend consumes these endpoints to provide a user-friendly interface.

## Features

- **Backend (GoApp)**:

  - RESTful API endpoints for user management (CRUD operations).
  - PostgreSQL database integration using the `database/sql` package.
  - Dockerized setup for easy deployment.

- **Frontend (NextApp)**:
  - User interface built with [INSERT_FRONTEND_TECHNOLOGY_HERE].
  - Consumes backend API endpoints to display and manage user data.
  - ...

## Prerequisites

Before running this project, ensure you have the following installed:

- [Docker](https://www.docker.com/)
- [NextJS] (https://nextjs.org/)

## Setup and Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/YOUR_USERNAME/fullstack-go-live.git
   ```

2. Navigate to the project directory:

   ```bash
   cd fullstack-go-live
   ```

3. Build and run the Docker containers:

   ```bash
   docker-compose up --build
   ```

4. Access the application:
   - Backend API: http://localhost:8000
   - Frontend UI: http://localhost:3000
