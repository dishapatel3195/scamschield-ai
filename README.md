# ScamShield AI

<div align="center">
  <img src="assets/logo.png" alt="ScamShield Logo" width="400">
</div>

A multi-input scam detection system that analyzes:
- Phone call transcripts
- Website content/URLs
- Email/offer letters
- Text messages

## Project Structure
scamshield-ai/
├── client/ # React + TypeScript frontend
├── server/ # Node.js + TypeScript backend
├── ai-service/ # Python AI processing
├── .gitignore
└── README.md


## Tech Stack

### Frontend
- React with TypeScript
- Chakra UI
- Axios for API calls

### Backend
- Node.js with Express
- TypeScript
- REST API architecture

### AI Service
- Python with FastAPI
- OpenAI/LangChain integration
- Web scraping capabilities

## Setup Guide

### Prerequisites
- Node.js (v18+)
- Python (3.9+)
- Git

### Installation

1. **Clone repository**
   ```bash
   git clone https://github.com/your-username/scamshield-ai.git
   cd scamshield-ai
Frontend Setup
bash
cd client
npm install
npm start
Backend Setup
bash
cd ../server
npm install
npm run dev
AI Service Setup
bash
cd ../ai-service
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt
uvicorn main:app --reload
Development

Running Locally

bash
# From project root
npm run dev  # Requires 'concurrently' installed globally
Environment Variables

Create .env files in each directory with required credentials.

Features

Real-time scam detection
Multiple input formats support
Detailed risk analysis
Historical scan records
Future Roadmap

Browser extension
Mobile app integration
Community reporting system
Advanced ML models
Contributing

Pull requests are welcome. For major changes, please open an issue first.