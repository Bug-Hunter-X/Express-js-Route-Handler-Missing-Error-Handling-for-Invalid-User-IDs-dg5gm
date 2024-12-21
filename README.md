# Express.js Route Handler Missing Error Handling for Invalid User IDs

This repository demonstrates a common error in Express.js route handlers: the lack of error handling for invalid input. Specifically, the provided code attempts to parse a user ID from the request parameters as an integer without verifying whether the ID is actually a number.

This can lead to unexpected crashes if a non-numeric ID is provided.

The `bug.js` file showcases the problematic code. The `bugSolution.js` file provides a corrected version with improved error handling.