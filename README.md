# Go Bank

This is a Go project that simulates a simple banking application.

## Project Structure

- [`Makefile`](command:_github.copilot.openRelativePath?%5B%22Makefile%22%5D "Makefile"): Contains commands for building, running, and testing the project.
- [`README.md`](command:_github.copilot.openRelativePath?%5B%22README.md%22%5D "README.md"): This file, which provides an overview of the project.
- [`api.go`](command:_github.copilot.openRelativePath?%5B%22api.go%22%5D "api.go"): Contains the API server logic for the banking application.
- [`bin/gobank`](command:_github.copilot.openRelativePath?%5B%22bin%2Fgobank%22%5D "bin/gobank"): The compiled binary of the application.
- [`go.mod`](command:_github.copilot.openRelativePath?%5B%22go.mod%22%5D "go.mod") and [`go.sum`](command:_github.copilot.openRelativePath?%5B%22go.sum%22%5D "go.sum"): Go module files that handle dependencies.
- [`main.go`](command:_github.copilot.openRelativePath?%5B%22main.go%22%5D "main.go"): The entry point of the application.
- [`types.go`](command:_github.copilot.openRelativePath?%5B%22types.go%22%5D "types.go"): Contains type definitions used in the project.

## Building the Project

You can build the project by running the following command:

```sh
make build
```

This will compile the Go files and output the executable binary to a directory named [`bin`](command:_github.copilot.openRelativePath?%5B%22bin%22%5D "bin") with the name `gobank`.

## Running the Project

You can run the project by using the following command:

```sh
make run
```

This command will build the project (if it hasn't been built already) and then run the compiled binary.

## Testing the Project

You can run the tests for the project with the following command:

```sh
make test
```

This command runs the tests in verbose mode for all packages in the current directory and its subdirectories.