# React Task Tracker Project

This project is a task tracker application built with React. It includes a user interface created with React and a backend powered by JSON-server.

## Getting Started

These instructions will guide you through the process of setting up the project on your local machine for development and testing purposes.

### Prerequisites

Before you begin, ensure that you have the following installed on your local machine:

- Node.js and npm (Node Package Manager). You can download these from Node.js official website.

### Installation

Follow these steps to set up and run the project:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/0ZMilad/task-tracker.git
    ```

2. **Navigate to the project directory**:
    ```bash
    cd task-tracker
    ```

3. **Install the dependencies**:
    ```bash
    npm install
    ```

### Running the Application

1. **Start the React development server** (this runs the app in the development mode and opens it in your default web browser):
    ```bash
    npm start
    ```
    Open http://localhost:3000 to view it in the browser.

2. **Start the JSON server** (this starts the backend server on your local machine):
    ```bash
    npm run server
    ```
    The server runs on http://localhost:5000.

### Building the Application

To build the app for production, use the following command. This builds the app for production to the `build` folder. It correctly bundles React in production mode and optimizes the build for the best performance:
    ```bash
    npm run build
    ```
