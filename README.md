
# Go Server

A simple HTTP server built using Go, featuring static file serving, form handling, and a basic Hello endpoint.

## Features

- Static HTML file serving
- POST form handling
- Name and address submission
- Hello endpoint

## Project Structure

```text
go-server/
├── main.go
├── go.mod
├── .gitignore
└── static/
    ├── index.html
    └── form.html
```

## Getting Started

### Prerequisites

- [Go](https://go.dev/dl/) installed

### Run Locally

```bash
git clone <repository-url>
cd go-server
go mod tidy
go run .
```

The server starts at:

http://localhost:8080

## Endpoints

| Endpoint | Method | Description |
|----------|--------|-------------|
| `/` | GET | Serves static files |
| `/form` | POST | Processes form submissions |
| `/hello` | GET | Returns Hello! |

## Build

```bash
go build
```

## License

MIT
