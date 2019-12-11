# minimal-http-server
No framework minimal http server built with Node.js

## Usage
Import the server in the Node project
`const server = require('./minimal-http-server');`

Start the server by calling `init()` method
`server.init()`

This will start the server on port 3000.

Alternatively, you can pass the port and hostname to the `init()` method.

`server.init(4000, 'localhost');`
