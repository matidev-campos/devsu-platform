## Architecture

- client-service: manages client lifecycle and emits domain events
- account-service: listens to client events and manages accounts
- Communication: async via RabbitMQ
- Database: PostgreSQL
- Orchestration: Docker Compose
