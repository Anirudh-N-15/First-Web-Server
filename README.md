# Basic Go Web Server

This is a simple web server written in Go that demonstrates handling HTTP requests, serving static files, and processing form submissions. It can be used as a starting point for learning Go's `net/http` package or building more complex web applications.

---

## Features
- **Serve Static Files**: Hosts files from a `./static` directory.
- **Handle GET Requests**: Responds to `/hello` endpoint with a "hello!" message.
- **Process POST Requests**: Handles form submissions at the `/form` endpoint and extracts `name` and `address` from the request body.

## How to Run on your PC
- Clone this repository 
- create a new directory and put the files index.html and form.html in the directory and give it a name "Static"
- open your terminal and make sure you have installed go before. Just check whether this command works "go --version". If not just install it and then first use the command "go build main.go" and then "go run main.go" or  "./main.go"
- Go to your browser's address bar and type in 'localhost:8080/form.html'
- You can also check 'localhost:8080/index.html'
- That's it

# This was my first ever web server. I know mistakes were commited :) .
  
