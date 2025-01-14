# Unhandled Promise Rejection in Node.js

This repository demonstrates a common error in Node.js applications: unhandled promise rejections.  Unhandled promise rejections can cause unexpected behavior and crashes. This example shows a simple HTTP server and how to properly handle potential errors to prevent unhandled rejections.

## Steps to Reproduce
1. Clone the repository.
2. Run `node server.js`.
3. You should see a message indicating the server is running on port 8080.  However, if you have an error causing an unhandled promise rejection, you'll likely see an error logged to your console.

## Solution
The solution involves using `.catch()` to handle potential rejections from promises.  See `serverSolution.js` for the corrected code.