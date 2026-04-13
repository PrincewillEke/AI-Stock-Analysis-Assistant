## AI Stock Analysis Assistant

An AI-powered stock analysis assistant built with FastAPI, LangChain, and yFinance. This project allows users to interact with stock market data through a conversational interface, combining real-time financial data retrieval with AI-generated insights.

## Features 

- Retrieve current stock prices
- View historical stock price data over a selected date range
- Access recent stock-related news
- View company balance sheet data
- Stream AI responses in real time
- Analyze stocks with technical indicators
- Generate AI-assisted stock recommendations

## Tech Stack

Frontend:

- React
- Vite
- Thesys GenUI SDK
- TypeScript
- CSS

Backend: 

- FastAPI
- Python
- Uvicorn
- yFinance (financial data)

AI Framework:

- LangChain
- Thesys API

## Installation & Setup

### 1. Clone the Repository

```bash
git clone 
cd ai-stock-analysis-assistant
```

### 2. Backend Setup

```bash
cd backend
uv sync
uv run python main.py
```

Backend runs at: http://localhost:8888

### 3. Frontend setup

```bash
cd frontend
npm install
npm run dev
```

Frontend runs at: http://localhost:5173











