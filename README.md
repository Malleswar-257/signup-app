# signup-app

Complete full-stack user signup application with pixel-perfect Figma design implementation. MUST generate ALL mandatory files - no shortcuts, no placeholders, complete working code only.

## Tech Stack

- **Frontend**: React + Vite
- **Backend**: FastAPI + SQLAlchemy
- **Design**: Figma ([View Design](https://www.figma.com/design/29HkCjsfiXv6gTPjrXmYwy/Sign-Up-Form--V1---Community-))

## Project Structure

```
signup-app/
├── frontend/          # Frontend application
├── backend/           # Backend API
├── README.md          # This file
└── docker-compose.yml # Docker configuration (if applicable)
```

## Getting Started

### Prerequisites

- Node.js 18+ (for frontend)
- Python 3.11+ (for Python backends)
- Docker (optional, for containerized setup)

### Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

### Backend Setup

```bash
cd backend
# Follow backend-specific setup instructions in backend/README.md
```

## Features

- User interface
- Data management
- User authentication
- Database integration

## API Endpoints

- `GET /` - Welcome message
- `GET /health` - Health check
- `POST /api/auth/register` - User registration
- `POST /api/auth/login` - User login
- `POST /api/auth/logout` - User logout
- `GET /api/auth/me` - Get current user

## License

MIT
