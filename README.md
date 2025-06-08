# AI Chat Assistant

A modern, FastAPI-based AI chat assistant with multimodal analysis capabilities.

## Features

- 🤖 AI-powered chat with context awareness
- 📝 User profile management
- 🖼️ Image analysis
- 🎵 Audio analysis
- 📊 Text analysis
- 🔒 Secure authentication
- 📈 Performance monitoring

## Quick Start

1. Clone the repository:
```bash
git clone https://github.com/yourusername/agent.git
cd agent
```

2. Create virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Set up environment variables:
```bash
cp .env.example .env
# Edit .env with your settings
```

5. Initialize database:
```bash
python src/utils/db_manager.py init
python src/utils/db_manager.py migrate
python src/utils/db_manager.py createsuperuser
```

6. Run the application:
```bash
python run.py
```

Visit `http://localhost:8000/api/v1/docs` for API documentation.

## API Endpoints

- `/api/v1/auth/*` - Authentication endpoints
- `/api/v1/chat` - Chat endpoints
- `/api/v1/profile` - Profile management
- `/api/v1/analyze/*` - Analysis endpoints

## Documentation

For detailed documentation, see [PROJECT.md](PROJECT.md).

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details. 