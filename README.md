# Mattermost Docker

This project provides a minimal setup to run [Mattermost](https://mattermost.com/) using Docker Compose.

## Usage

1. Clone this repository.
2. Copy the example environment file: `cp .env.example .env`
3. Edit `.env` to set your desired configuration (e.g., database password, Mattermost site URL).
4. Run `docker compose up -d` to start the services.
5. Access Mattermost at `http://localhost:8065`.
