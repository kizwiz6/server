# NodeDev Node.js Training

## server

Setting up first Node.js application.

The code does the following:
- It defines a variable for the server's port. This can be passed on the command line, a PORT environment variable, or it falls back to 3000.
- It uses the HTTP createServer library to create a web server which listens on that port. When its callback function receives a request, it can examine the details in the req object and return a response using the res object.
