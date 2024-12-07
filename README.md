# Basic Go Web Server

This is a simple web server written in Go that demonstrates handling HTTP requests, serving static files, and processing form submissions. It can be used as a starting point for learning Go's `net/http` package or building more complex web applications.

---

## Features
- **Serve Static Files**: Hosts files from a `./static` directory.
- **Handle GET Requests**: Responds to `/hello` endpoint with a "hello!" message.
- **Process POST Requests**: Handles form submissions at the `/form` endpoint and extracts `name` and `address` from the request body.
