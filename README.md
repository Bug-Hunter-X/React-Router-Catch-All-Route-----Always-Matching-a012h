# React Router Catch-All Route Issue

This repository demonstrates a common issue with React Router's catch-all route (`*`). The catch-all route, intended to handle 404 errors, is incorrectly configured to always match, preventing other routes from rendering correctly.

The `bug.js` file shows the problematic code.  The `bugSolution.js` file provides a corrected implementation.

## How to Reproduce
1. Clone the repository.
2. Run `npm install` to install dependencies.
3. Run `npm start` to start the development server.
4. Observe that navigating to any route (e.g., `/about`) will always display the 404 page.