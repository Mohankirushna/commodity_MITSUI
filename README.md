# 🌾 Commodity Price Prediction Platform

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.9+](https://img.shields.io/badge/python-3.9+-blue.svg)](https://www.python.org/downloads/)

## 📋 Project Overview
A full-stack platform for commodity price prediction and market analysis using ML and custom LLMs, built on the [MITSUI Commodity Prediction Challenge](https://www.kaggle.com/competitions/mitsui-commodity-prediction-challenge) dataset.

## ✨ Key Features
- **📈 Price Prediction**: Multi-horizon forecasting with ML/DL models
- **🤖 Custom LLM**: Domain-specific language model for market analysis
- **📊 Interactive Dashboard**: Real-time visualization and insights
- **🔍 Market Sentiment Analysis**: News and report analysis

## 🛠 Tech Stack
- **Frontend**: React, TypeScript, Redux, Chart.js
- **Backend**: FastAPI, PostgreSQL, Redis
- **ML**: PyTorch, Transformers, Scikit-learn
- **Infra**: Docker, Kubernetes, AWS/GCP
- **LLM**: Custom fine-tuned model for commodity markets

## Project Structure
```
commodity-ai/
├── frontend/      # React app
├── backend/       # FastAPI server
├── ml/            # ML models & training
└── llm/           # Custom LLM development
```

## Getting Started
1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/commodity-ai.git
   cd commodity-ai
   ```

2. Set up backend:
   ```bash
   cd backend
   python -m venv venv
   source venv/bin/activate  # Windows: .\venv\Scripts\activate
   pip install -r requirements.txt
   ```

3. Set up frontend:
   ```bash
   cd ../frontend
   npm install
   npm start
   ```

4. Run ML training:
   ```bash
   cd ../ml
   python train.py
   ```

## Dataset
- Source: [MITSUI Commodity Prediction Challenge](https://www.kaggle.com/competitions/mitsui-commodity-prediction-challenge)
- Preprocessing scripts in `ml/data/`

## License
MIT License - See LICENSE for details.
