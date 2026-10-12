# LinkForge

LinkForge is a web application built with **React** on the client and **Express** on the server.

## Tech stack

- React and JavaScript for the user interface
- Express and Node.js for the server and API

## Getting started

### Prerequisites

- Node.js (LTS recommended)
- npm (included with Node.js)

### Install dependencies

From the project root, install the dependencies:

```bash
npm install
```

If the client and server have separate `package.json` files, install dependencies in each application directory as well:

```bash
cd client && npm install
cd ../server && npm install
```

### Run the application

Start the client and server using the scripts defined in their respective `package.json` files. For example, projects commonly use:

```bash
npm run dev
```

When client and server are separate applications, open two terminals and run the development script in each directory:

```bash
cd server && npm run dev
```

```bash
cd client && npm run dev
```

The exact commands and local URLs depend on the scripts and configuration in this project.

## Project structure

The client and server may be organized in separate directories. A common layout is:

```text
.
├── client/   # React application
└── server/   # Express application and API
```

## Configuration

If the application uses environment variables, create a `.env` file in the directory expected by the server and set the required values. Keep secrets out of source control. See an `.env.example` file if the project provides one.

## Available scripts

Run `npm run` in an application directory to list its available npm scripts. The scripts in `package.json` are the source of truth for development, build, and test commands.
