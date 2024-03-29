# Project Management Web Application

## Overview
This is a simple web application for managing projects and tasks. Users can add new tasks, view the list of tasks, and mark tasks as completed.

## Running the Application Locally
To run the application locally, follow these steps:
1. Clone this repository to your local machine.
2. Navigate to the project directory in your terminal.
3. Open the `index.html` file in a web browser.

## Building the Docker Image and Running a Container
To build the Docker image and run a container using the image, follow these steps:
1. Ensure Docker is installed on your system.
2. Clone this repository to your local machine if you haven't already.
3. Navigate to the project directory in your terminal.
4. Build the Docker image using the provided Dockerfile:

   
Certainly! Here's a brief README.md documentation explaining how to run the application locally, build the Docker image, and run a container using the image, along with any assumptions or decisions made during the development process:

markdown
Copy code
# Project Management Web Application

## Overview
This is a simple web application for managing projects and tasks. Users can add new tasks, view the list of tasks, and mark tasks as completed.

## Running the Application Locally
To run the application locally, follow these steps:
1. Clone this repository to your local machine.
2. Navigate to the project directory in your terminal.
3. Open the `index.html` file in a web browser.

## Building the Docker Image and Running a Container
To build the Docker image and run a container using the image, follow these steps:
1. Ensure Docker is installed on your system.
2. Clone this repository to your local machine if you haven't already.
3. Navigate to the project directory in your terminal.
4. Build the Docker image using the provided Dockerfile:

During the development process, the following assumptions and decisions were made:

Lightweight and simplicity: The application was kept simple without using any external libraries or frameworks to keep it lightweight and easy to deploy.
Basic features: The application focuses on essential features such as adding tasks, viewing tasks, and marking tasks as completed to meet the minimum viable product (MVP) requirements.
Docker containerization: Docker was chosen for containerization to ensure easy deployment and scalability of the application across different environments.
Exposed port: The application runs on port 80 inside the Docker container, so port 8080 on the host is mapped to port 80 in the container for accessing the application.
