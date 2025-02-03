# Node.js Port Already in Use Error

This repository demonstrates a common error in Node.js: the 'port already in use' error.  The `bug.js` file contains code that attempts to start a server on port 8080. If another process is already using this port, the server will fail to start, throwing an error.

The `bugSolution.js` file provides a solution that gracefully handles this situation by checking if the port is available before attempting to start the server.