# Student Management System — Frontend

This is the **frontend** component of the Student Management System, a web application built using React, Redux, and Material-UI. It works in tandem with the backend (Node.js + Express + MongoDB) to provide a full-stack solution for managing students, teachers, classes, attendance, and communication.

## Table of Contents

- [Features](#features)  
- [Tech Stack](#tech-stack)  
- [Prerequisites](#prerequisites)  
- [Setup & Installation](#setup--installation)  
- [Available Scripts](#available-scripts)  
- [Environment Variables](#environment-variables)  
- [Folder Structure](#folder-structure)  
- [Troubleshooting / Common Issues](#troubleshooting--common-issues)  
- [Contributing](#contributing)  
- [License](#license)  

## Features

- Role-based access: Admin, Teacher, Student  
- Dashboards for each role  
- Attendance marking & reports  
- Performance / marks entry and view  
- Messaging / communication between teachers and students  
- Data visualization for student performance  
- Responsive UI using Material-UI components  

## Tech Stack

- React  
- Redux (for state management)  
- Material-UI (UI component library)  
- Axios (for API calls)  
- React Router (for routing)  
- Others (e.g. Chart.js or similar)  

## Prerequisites

- Node.js (v14 or above recommended)  
- npm or yarn  
- A running backend server (Node.js + Express) with access to MongoDB  
- The backend’s API endpoints must be accessible (e.g. `http://localhost:5000`)

## Setup & Installation

1. Clone / navigate to your frontend folder:

   ```bash
   cd frontend
Install dependencies:

npm install
# or
yarn install


Configure environment variables (see Environment Variables
).

Start the development server:

npm start
# or
yarn start


Open your browser and navigate to http://localhost:3000.

Make sure your backend is running (commonly at localhost:5000) so the frontend can communicate with APIs.

Available Scripts

In the frontend directory, you’ll find some useful npm scripts:

Script	Description
npm start	Starts the development server
npm run build	Builds the app for production deployment
npm test	Runs tests (if set up)
npm run lint	Runs linting (if configured)

(Adjust or add scripts as needed.)

Environment Variables

Create a .env file in the frontend folder to hold configuration variables. Example:

REACT_APP_BASE_URL=http://localhost:5000


REACT_APP_BASE_URL: The base URL for API calls (backend server).

Other environment variables can be added as needed (e.g. feature toggles, analytics keys, etc.).

Note: In some cases, .env files may not load properly in all environments. If you run into errors (e.g. network requests failing, infinite loading), you can fallback by directly using a constant in code or ensuring process.env.REACT_APP_BASE_URL is properly read.