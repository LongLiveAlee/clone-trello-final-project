# Cloning Trello

This is a RESTful API forTrello is the visual work management tool that empowers teams to ideate, plan, manage, and celebrate their work together in a collaborative, productive, and organized way.

## Getting Started

### Prerequisites

- Go 1.19 or later
- PostgreSQL database
- GIN framework
- GORM library

### Installation

1. Clone the repository:

   ```bash
   git clone ...
   cd your-repository
   docker compose -f ./docker/database/docker-compose.yaml up -d
   cd app
   ```

2. Install the required Go modules:

   ```bash
   go mod tidy
   ```

### Running the Server

To run the server, use the following command:

```bash
go build && ./go-auth
```

This will start the API server at http://localhost:3030.
