# 🧠 Mood Journal Bot

<div align="center">

[![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![Ollama](https://img.shields.io/badge/Ollama-Local_LLM-black?style=for-the-badge&logo=ollama&logoColor=white)](https://ollama.com)
[![Streamlit](https://img.shields.io/badge/Streamlit-UI-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)](https://streamlit.io)
[![Docker](https://img.shields.io/badge/Docker-Ready-2496ED?style=for-the-badge&logo=docker&logoColor=white)](https://docker.com)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

**AI-Powered Mood Journaling Chatbot — Personalized Mental Wellness at Your Fingertips**

[Features](#-features) • [Quick Start](#-quick-start) • [Architecture](#-architecture) • [Tech Stack](#-tech-stack)

</div>

---

## 🎯 One-Liner

Conversational AI journal that understands your emotions, tracks mood patterns, and provides personalized insights — powered by local Gemma 4 LLM via Ollama. 100% private. Your data never leaves your machine.

---

## 🏗️ Architecture

```
┌────────────────────────────────┐
│   Streamlit Web Interface      │
│   - Mood input form            │
│   - Journal entries            │
│   - Pattern visualization      │
└────────────────┬───────────────┘
                 │
┌────────────────▼───────────────┐
│   Journal Processing Engine    │
│   - Sentiment analysis         │
│   - Mood classification        │
│   - Pattern detection          │
│   - Insight generation         │
└────────────────┬───────────────┘
                 │
┌────────────────▼───────────────┐
│   Ollama (Local LLM)           │
│   - Gemma 4 or Llama3.2        │
│   - Conversational responses   │
│   - Zero cloud transmission    │
└────────────────────────────────┘
```

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 💬 **Conversational Journal** | Chat with your AI journal in natural language |
| 🧠 **Emotion Recognition** | Detects emotional patterns from journal entries |
| 📊 **Mood Tracking** | Visual charts showing mood trends over time |
| 🔍 **Pattern Analysis** | AI-powered insights into your emotional patterns |
| 📝 **Voice Journal** | Speak your thoughts (transcribed locally if enabled) |
| 🎯 **Personalized Insights** | Tailored suggestions based on your mood history |
| 🔐 **100% Private** | No cloud servers, no data tracking — local processing only |
| 📱 **Mobile Responsive** | Access your journal from any device via browser |
| 🎨 **Beautiful UI** | Streamlit interface with dark mode support |
| 🐳 **Docker Ready** | One-command deployment with Docker Compose |

---

## 🚀 Quick Start

### Prerequisites

- **Python 3.10+**
- **Ollama** installed and running ([ollama.com](https://ollama.com))
- A local LLM model (e.g., `ollama pull gemma4`)

### Installation

```bash
# Clone the repository
git clone https://github.com/kennedyraju55/mood-journal-bot.git
cd mood-journal-bot

# Create virtual environment
python -m venv venv
source venv/bin/activate  # Linux/Mac
# venv\Scripts\activate    # Windows

# Install dependencies
pip install -r requirements.txt
```

### First Run

```bash
# Start Ollama (if not already running)
ollama serve

# Pull a model (first time only)
ollama pull gemma4

# Run the web UI
streamlit run app.py
```

### Docker Deployment

```bash
git clone https://github.com/kennedyraju55/mood-journal-bot.git
cd mood-journal-bot
docker compose up
# Open http://localhost:8501
```

---

## 🛠️ Tech Stack

| Component | Technology |
|-----------|-----------|
| **Language** | Python 3.10+ |
| **Web Framework** | Streamlit |
| **Local LLM** | Ollama (Gemma 4 / Llama3.2) |
| **Data Processing** | pandas, NumPy |
| **Sentiment Analysis** | TextBlob / VADER |
| **Visualization** | Matplotlib, Plotly |
| **Storage** | SQLite / JSON |
| **Containerization** | Docker & Docker Compose |

---

## 📂 Project Structure

```
mood-journal-bot/
├── src/
│   └── mood_journal/
│       ├── __init__.py
│       ├── core.py              # Mood analysis logic
│       ├── llm.py               # Ollama integration
│       ├── database.py          # Journal storage
│       └── sentiment.py         # Emotion detection
├── app.py                       # Streamlit main app
├── tests/                       # Test suite
├── config.yaml                  # Configuration
├── Dockerfile                   # Container setup
├── docker-compose.yml           # Full stack
├── requirements.txt             # Dependencies
└── README.md
```

---

## 📖 Usage Examples

### Start Journaling
1. Open http://localhost:8501
2. Type your mood and thoughts
3. Chat with your AI journal
4. Get personalized insights

### View Mood Trends
- Visual charts showing emotional patterns
- Weekly and monthly summaries
- Triggered mood factors

### Export Journal
- Download entries as JSON or CSV
- Privacy-first — stays on your machine

---

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

---

## 📄 License

MIT License — see [LICENSE](LICENSE) for details.

---

## 👤 Author

**Nrk Raju Guthikonda**  
Senior Software Engineer @ Microsoft • Copilot Search Infrastructure

- 🔗 [GitHub](https://github.com/kennedyraju55)
- 💼 [LinkedIn](https://linkedin.com/in/nrk-raju-guthikonda-504066a8/)
- ✍️ [dev.to](https://dev.to/kennedyraju55)
- 📧 [Email](mailto:rajug058@gmail.com)

---

<div align="center">

**Your mental wellness journey, powered by local AI — completely private, always available**

[⬆ Back to Top](#-mood-journal-bot)

</div>
