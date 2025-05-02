# ScamShield AI

<div align="center">
  <img src="logo.png" alt="ScamShield Logo" width="400">
</div>

A multi-input scam detection system that analyzes:
- Phone call transcripts
- Website content/URLs
- Email/offer letters
- Text messages

## Project Structure
scamshield-ai/
  └── client/ 
  └── server/ 
  └── ai-service/ 
  └── .gitignore
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
   - git clone https://github.com/your-username/scamshield-ai.git
   - cd scamshield-ai
2. **Frontend Setup**
   - cd client
   - npm install
   - npm start
3. **Backend Setup**
   - cd ../server
   - npm install
   - npm run dev
4. **AI Service Setup**
   - cd ../ai-service
   - python -m venv venv
   - source venv/bin/activate
   - pip install -r requirements.txt
   - uvicorn main:app --reload
5. **Development**
   - npm run dev  