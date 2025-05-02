SCAM SHIELD AI Personal Project

Workspace Structure:
    scamshield-ai/
    ├── client/          
    ├── server/          
    ├── ai-service/      
    ├── .gitignore
    └── README.md


client: React + TypeScript frontend
server: Node.js + TypeScript backend
ai-service: Python AI processing 

Setup: 
1. git init
2. build project structure
3. setup frontend in client
    a. build frontend react: npx create-react-app . --template typescript
    b. add dependencies: npm install @chakra-ui/react @emotion/react @emotion/styled framer-motion axios react-icons
    c. add react development extensions: ESLint, Prettier, and Reactjs code snippets
4. setup backend in server
    a. add dependencies: npm install express typescript ts-node @types/express @types/node cors axios
    b. add more depencies: npm install --save-dev nodemon eslint prettier
    c. initialize typescirpt: npx tsc --init
5. setup python ai service
    a. add python: python -m venv venv
    b. activate virtual enviornment: source venv/bin/activate
    c. install python packages: pip install fastapi uvicorn python-multipart openai langchain beautifulsoup4 pdfminer.sixc
