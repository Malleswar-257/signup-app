# Signup-App Backend

Complete full-stack user signup application with pixel-perfect Figma design implementation. MUST generate ALL mandatory files - no shortcuts, no placeholders, complete working code only.

## Setup

1. Create virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the server:
   ```bash
   python main.py
   ```

4. Visit http://localhost:8000/docs for API documentation

## API Endpoints

- `GET /` - Welcome message
- `GET /health` - Health check
- `GET /items/` - List items
- `POST /items/` - Create item

## Built With

- FastAPI
- SQLAlchemy
- SQLite (default)
- Uvicorn