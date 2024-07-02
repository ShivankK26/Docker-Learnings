# Docker Learnings

Welcome to the Docker Learnings Repository! This Repository contains all the source code and resources needed to learn how to dockerize various applications, including a MERN application, React application, Vite application, and Next.js app.

## Table of Contents

- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Dockerizing Applications](#dockerizing-applications)
  - [MERN Application](#mern-application)
  - [React Application](#react-application)
  - [Vite Application](#vite-application)
  - [Next.js Application](#nextjs-application)
- [Resources](#resources)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This repository is designed to help you learn Docker by providing practical examples of dockerizing different types of applications. Each project folder contains the necessary Docker configuration files and a step-by-step guide to help you understand the process.

## Prerequisites

Before you begin, make sure you have the following installed:

- [Docker](https://www.docker.com/get-started)
- [Node.js](https://nodejs.org/)
- [Git](https://git-scm.com/)

## Getting Started

1. Clone the repository:
    ```bash
    git clone https://github.com/ShivankK26/Docker-Learnings.git
    cd Docker-Learnings
    ```

2. Follow the instructions in each project folder to learn how to dockerize the specific application.

## Project Structure

The repository is organized into the following directories:

- `mern-app/`: Contains the source code and Docker configuration for a MERN application.
- `react-app/`: Contains the source code and Docker configuration for a React application.
- `vite-app/`: Contains the source code and Docker configuration for a Vite application.
- `nextjs-app/`: Contains the source code and Docker configuration for a Next.js application.

## Dockerizing Applications

### MERN Application

The `mern-app` directory contains a full-stack MERN application. Follow the steps below to dockerize it:

1. Navigate to the `mern-app` directory:
    ```bash
    cd mern-app
    ```

2. Build the Docker image:
    ```bash
    docker build -t mern-app .
    ```

3. Run the Docker container:
    ```bash
    docker run -p 3000:3000 mern-app
    ```

### React Application

The `react-app` directory contains a React application. Follow the steps below to dockerize it:

1. Navigate to the `react-app` directory:
    ```bash
    cd react-app
    ```

2. Build the Docker image:
    ```bash
    docker build -t react-app .
    ```

3. Run the Docker container:
    ```bash
    docker run -p 3000:3000 react-app
    ```

### Vite Application

The `vite-app` directory contains a Vite application. Follow the steps below to dockerize it:

1. Navigate to the `vite-app` directory:
    ```bash
    cd vite-app
    ```

2. Build the Docker image:
    ```bash
    docker build -t vite-app .
    ```

3. Run the Docker container:
    ```bash
    docker run -p 3000:3000 vite-app
    ```

### Next.js Application

The `nextjs-app` directory contains a Next.js application. Follow the steps below to dockerize it:

1. Navigate to the `nextjs-app` directory:
    ```bash
    cd nextjs-app
    ```

2. Build the Docker image:
    ```bash
    docker build -t nextjs-app .
    ```

3. Run the Docker container:
    ```bash
    docker run -p 3000:3000 nextjs-app
    ```

## Resources

Here are some additional resources to help you learn Docker:

- [Docker Documentation](https://docs.docker.com/)
- [Node.js Docker Best Practices](https://nodejs.org/en/docs/guides/nodejs-docker-webapp/)
- [Dockerizing a React App](https://mherman.org/blog/dockerizing-a-react-app/)
- [Next.js Docker Example](https://nextjs.org/docs/deployment#docker-image)

