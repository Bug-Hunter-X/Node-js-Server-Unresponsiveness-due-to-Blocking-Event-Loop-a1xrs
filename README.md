# Node.js Server Unresponsiveness

This repository demonstrates a common issue in Node.js: server unresponsiveness caused by blocking the event loop with a long-running synchronous operation.  The `blocking_server.js` file shows the problematic code. The solution (`non_blocking_server.js`) demonstrates how to fix it using asynchronous operations.