cat > README.md << 'EOF'
# Beam Analysis AI Tool

[![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)](https://fastapi.tiangolo.com/)
[![OpenAI](https://img.shields.io/badge/OpenRouter-000000?style=for-the-badge&logo=openai&logoColor=white)](https://openrouter.ai/)
[![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=for-the-badge&logo=chartdotjs&logoColor=white)](https://www.chartjs.org/)

A powerful, AI-powered web application for structural engineers and students. Describe a beam in plain language, and the tool automatically calculates support reactions and generates interactive Shear Force (V(x)) and Bending Moment (M(x)) diagrams.

## ✨ Features

- **🤖 AI-Powered Parsing**: Input natural language descriptions of beams
- **🧮 Analytical Engine**: Calculates support reactions, shear forces, and bending moments
- **📊 Interactive Visualization**: Chart.js diagrams for shear and moment values
- **🔧 RESTful API**: Fully documented API for developers
- **📱 Responsive UI**: Works on desktop and mobile devices

## 🛠️ Tech Stack

### Backend
- **Framework**: [FastAPI](https://fastapi.tiangolo.com/) (Python)
- **AI Integration**: [OpenRouter API](https://openrouter.ai/) (GPT-4o)
- **Numerical Computing**: [NumPy](https://numpy.org/)
- **HTTP Client**: [HTTPX](https://www.python-httpx.org/)
- **ASGI Server**: [Uvicorn](https://www.uvicorn.org/)
- **Environment Management**: [python-dotenv](https://pypi.org/project/python-dotenv/)

### Frontend
- **Charts**: [Chart.js](https://www.chartjs.org/)
- **Styling**: Vanilla CSS3
- **Language**: Vanilla JavaScript (ES6+)

## 🚀 Quick Start & Installation

### Prerequisites
- Python 3.8+
- `pip` (Python package manager)

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/beam-analysis-ai-tool.git
cd beam-analysis-ai-tool
