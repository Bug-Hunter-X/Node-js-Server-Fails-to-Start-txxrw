# Node.js Server Startup Issue

This repository demonstrates a common issue encountered when starting a Node.js HTTP server: port conflicts or permission problems.

The `bug.js` file contains code that attempts to start a server on port 8080. If this port is already in use by another application, or if the user doesn't have sufficient permissions to bind to this port, the server will fail to start.

The `bugSolution.js` file provides a solution to address this problem.