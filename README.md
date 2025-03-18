# Tech Quiz

A full-stack application that provides a quiz interface for technical questions, built with React and Express.

## Features

- Interactive quiz interface
- Random question selection
- Score tracking
- Responsive design

## Technology Stack

- **Frontend**: React, TypeScript, Bootstrap
- **Backend**: Express, Node.js, MongoDB
- **Testing**: Cypress (Component Testing)
- **CI/CD**: GitHub Actions

## Setup Instructions

1. Clone the repository

```bash
git clone <repository-url>
cd tech-quiz
```

2. Install dependencies

```bash
npm install
```

3. Set up environment variables

- Copy `server/.env.EXAMPLE` to `server/.env`
- Configure MongoDB connection string if needed

4. Seed the database

```bash
npm run seed
```

5. Start development servers

```bash
npm run develop
```

## Testing

Run component tests using Cypress:

```bash
npm run test
```

Or run the Cypress test UI:

```bash
npm run test-gui
```

## Deployment

The application is configured for automatic deployment to Render using GitHub Actions when code is merged to the main branch.

- Render Deployment: [Render-Link](https://github-actions-gmgy.onrender.com)

## Project Structure

- `/client` - React frontend application
- `/server` - Express backend API
- `/cypress` - Component tests

## Author

Developed by Christian Walters

- GitHub: [github.com/EnderJunk](https://github.com/EnderJunk)

## Application Screenshot

![Tech Quiz Application Screenshot](./assets/Capture.png)

---

**[Back To Top](#tech-quiz)**
