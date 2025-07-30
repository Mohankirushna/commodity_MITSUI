# Commodity Price Prediction & Analysis Platform

## Project Overview
A full-stack web application for commodity price prediction using ML and custom LLMs, built on the MITSUI Commodity Prediction Challenge dataset.

## Key Features
- **Price Prediction**: Time-series forecasting with multiple ML models
- **Custom LLM**: Domain-specific language model for commodity markets
- **Interactive Dashboard**: Real-time visualization and analysis

## Tech Stack
- **Frontend**: React, TypeScript, Redux, Chart.js
- **Backend**: FastAPI, PostgreSQL, Redis
- **ML**: PyTorch, Scikit-learn, Transformers
- **Infra**: Docker, Kubernetes, AWS/GCP

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
