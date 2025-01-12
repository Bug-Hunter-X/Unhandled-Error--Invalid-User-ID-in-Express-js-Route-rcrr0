# Unhandled Error: Invalid User ID in Express.js Route

This repository demonstrates a common error in Express.js route handlers:  lack of error handling for invalid input.  The `bug.js` file shows a route that attempts to parse a user ID from the request parameters without checking if it's a valid number. This can lead to unexpected behavior or crashes if a non-numeric ID is provided.

The `bugSolution.js` file provides a corrected version with proper error handling, showcasing how to gracefully handle invalid input and prevent errors.