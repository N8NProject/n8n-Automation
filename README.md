# n8n Workflows

This repository contains n8n workflows and their configuration.

## Setup

1. Clone this repository
2. Start the services using Docker Compose:
   ```bash
   docker-compose up -d
   ```
3. Access n8n at http://localhost:5678

## Workflows

Workflows are stored in the `workflows/` directory. Each workflow can be imported into n8n using the import functionality.

## Configuration

The project uses Docker Compose for orchestration with the following services:
- n8n: Workflow automation platform
- PostgreSQL: Database for n8n

## Security Notes

- Default credentials are set for development purposes only
- For production use, please change the following:
  - PostgreSQL credentials
  - N8N_ENCRYPTION_KEY
  - Other security-related environment variables 