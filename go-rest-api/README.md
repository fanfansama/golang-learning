# golang-learning

[lecture]{https://dev.to/aurelievache/learning-go-by-examples-part-2-create-an-http-rest-api-server-in-go-1cdm)

# run it

$ go run internal/main.go

$ curl localhost:8080

# build it

$ go build -o bin/go-rest-api internal/main.go

# Make file

[lecture]{https://dev.to/stack-labs/introduction-to-taskfile-a-makefile-alternative-h92)

$ task list

# execute it

$ ./bin/go-rest-api



# For Linux:

## Linux 32 bits
$ GOOS=linux GOARCH=386 go build -o bin/go-rest-api-linux-386 internal/main.go

## Linux 64 bits
$ GOOS=linux GOARCH=amd64 go build -o bin/go-rest-api-linux-64 internal/main.go