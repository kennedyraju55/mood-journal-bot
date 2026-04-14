# 🌙 Mood Journal Bot

![Python Version](https://img.shields.io/badge/Python-3.11+-blue?style=for-the-badge&logo=python)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
![Gemma 3](https://img.shields.io/badge/AI-Gemma%203-orange?style=for-the-badge)
![Privacy First](https://img.shields.io/badge/Privacy-First-purple?style=for-the-badge&logo=lock)
![Ollama](https://img.shields.io/badge/Ollama-Local%20AI-black?style=for-the-badge)

> AI emotion analysis and journaling for mental wellbeing tracking

## 📋 Overview

Advanced AI-powered application leveraging Gemma 3 for intelligent analysis and personalized recommendations.

## 🏗️ Architecture

\\\
┌─────────────────────────────────────────────────────┐
│                   User Interface                      │
│              (Web/Mobile/CLI Frontend)               │
└────────────────┬────────────────────────────────────┘
                 │
┌────────────────▼────────────────────────────────────┐
│               API Gateway Layer                       │
│        (Request Handling & Validation)               │
└────────────────┬────────────────────────────────────┘
                 │
┌────────────────▼────────────────────────────────────┐
│           Business Logic Services                     │
│     (Core Processing & Orchestration)                │
└────┬─────────────┬──────────────────┬───────────────┘
     │             │                  │
┌────▼──┐  ┌──────▼────┐  ┌──────────▼────┐
│ Gemma │  │   Data    │  │  Integration  │
│   3   │  │Persistence│  │  Services     │
│  Model│  │  Layer    │  │               │
└───────┘  └────────────┘  └─────┬────────┘
           │                      │
    ┌──────▼──────────────────────▼────┐
    │   Privacy-First Local Ollama      │
    │   (Offline AI Processing)         │
    └───────────────────────────────────┘
\\\

## ✨ Key Features

- Real-time mood tracking with emotion classification
- AI-powered journaling with sentiment analysis
- Pattern recognition for mood triggers
- Mental health trend monitoring
- Contextual suggestions based on mood history
- Privacy-protected local processing
- Beautiful mood calendar and statistics
- Guided journaling prompts
- Wellness recommendations
- Secure data encryption

## 🚀 Quick Start

### Prerequisites

- Python 3.11+
- pip (Python package manager)
- Ollama (optional, for local AI processing)
- Git

### Installation

1. **Clone the repository**
   \\\ash
   git clone https://github.com/kennedyraju55/mood-journal-bot.git
   cd mood-journal-bot
   \\\

2. **Create a virtual environment**
   \\\ash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\\Scripts\\activate
   \\\

3. **Install dependencies**
   \\\ash
   pip install -r requirements.txt
   \\\

4. **Configure environment (optional)**
   \\\ash
   cp .env.example .env
   \\\

### Running the Application

\\\ash
# Start the main application
python main.py

# Development mode with hot reload
python main.py --dev

# Local Ollama mode (privacy-first)
python main.py --local
\\\

## 🛠️ Tech Stack

| Component | Technology | Purpose |
|-----------|-----------|---------|
| **AI/ML** | Gemma 3, Ollama | Intelligent analysis |
| **Backend** | Python 3.11+ | Core logic |
| **API** | FastAPI/Flask | REST endpoints |
| **Database** | SQLite/PostgreSQL | Data persistence |
| **Frontend** | React/Vue | User interface |
| **Deployment** | Docker | Containerization |
| **Testing** | Pytest | Quality assurance |

## �� Project Structure

\\\
.
├── src/
│   ├── main.py              # Entry point
│   ├── api/                 # API endpoints
│   ├── models/              # Data models
│   ├── services/            # Business logic
│   └── utils/               # Utilities
├── tests/                   # Test suite
├── docs/                    # Documentation
├── requirements.txt         # Dependencies
└── README.md               # This file
\\\

## 👨‍💻 Author

**Raju Guthikonda** (kennedyraju55)

- 🔗 [GitHub](https://github.com/kennedyraju55)
- 📝 [Dev.to](https://dev.to/kennedyraju55)
- 💼 [LinkedIn](https://linkedin.com/in/nrk-raju-guthikonda-504066a8)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.

---

<div align="center">
  <b>Made with ❤️ using Gemma 3 and Ollama</b><br>
  ⭐ Star this repo if you find it helpful!
</div>