# Learning HTMX and Go

We are using templating to render a simple static html page that counts the number of visits.

To spin up the server, we are using Golang with the following packages

- Echo - HTML Server
- Air - Live reload 

You can install these with the following commands 
``` bash
go install github.com/cosmtrek/air@latest
go get github.com/labstack/echo/v4
go get github.com/labstack/echo/v4/middleware
```

To run the server execute 
```bash
air // Listens to the current project's files for changes
```

 
