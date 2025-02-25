# Agent Builder Platform

A modular platform for building and managing AI agents, consisting of three main components:
- Frontend (Next.js UI)
- Middleware (API Layer)
- Botpress SDK Integration

## Architecture

The platform follows a microservices architecture:
- **Frontend**: Next.js application providing the user interface
- **Middleware**: Express.js API layer handling requests and SDK communication
- **Botpress SDK**: Core SDK running in isolated containers per client

## Development Setup

### Prerequisites
- Node.js 18+
- Docker and Docker Compose
- Git

### Local Development

1. Clone the repository:
```bash
git clone <repository-url>
cd agent-builder
```

2. Start the development environment:
```bash
docker-compose up -d
```

3. Access the application:
- Frontend: http://localhost:3000
- Middleware API: http://localhost:3001

## Project Structure

```
agent-builder/
├── frontend/           # Next.js frontend application
├── middleware/         # Express.js API layer
├── sdk/               # Botpress SDK integration
└── docker-compose.yml # Container orchestration
```

## Contributing

1. Create a feature branch
2. Make your changes
3. Submit a pull request

## License

Private repository - All rights reserved