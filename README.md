# go-service-template

Template for building web services in golang. Uses gorilla/mux as a router/dispatcher.

This includes routing, logging, json serialization

### How to run

`go run main.go` works well if your application or service has a single file, but for a more complex project with lots of files then you'll have to start using the proper go build tool and run the compiled executable.

```
go build && service.exe
```

`go build` will generate an executable called `service.exe` (on windows) and then run that executable by typing `service.exe`.

The app will bind itself to port 3030 (defined in `main.go`).