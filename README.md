# Fastapi-React-Mongodb-Docker

## Overview

This project provides a complete template to get started with a full-stack application using FastAPI, React, MongoDB, and Docker. It includes JWT-based user authentication through FastAPIUsers.

## Project Structure

The project is composed of:

- **Backend API Server:**
  - Built with FastAPI and located in the [backend](backend) directory.
  - Provides APIs for user authentication, data management, and other backend services.
  - Integrates with MongoDB for database operations.
  
- **Frontend Web App:**
  - Built with React and located in the [frontend](frontend) directory.
  - Uses React-Bootstrap for styling and React-Icons for icons.
  - Implements routing with React-Router.
  - Communicates with the FastAPI backend for data fetching and state management.

## Features

- **React Frontend:**
  - Integrated with React-Bootstrap for responsive design.
  - Utilizes React-Icons for a comprehensive icon library.
  - Implements routing and state management.

- **Authentication System:**
  - Uses JWT token authentication via the FastAPIUsers project.
  - Provides secure authentication and authorization mechanisms.
  
- **Routing Examples:**
  - Demonstrates how to create both protected and regular routes using FastAPIUsers on the backend.
  - Uses React-Router on the frontend for navigation.

- **MongoDB Integration:**
  - Defines MongoDB collection schemas using Pydantic.
  - Shows how to extend the "users" collection with additional attributes.

- **Docker Configuration:**
  - Docker configuration files for easy setup and deployment.
  - Supports both development and production environments.

## Running the Application with Docker

The project contains Docker configuration files to run the application with Docker Compose. Two Docker Compose files are provided with configurations for `dev` and `production` environments.

### Local Development with Docker

The local development configuration file for Docker is [docker-compose.yml](./docker-compose.yml).
