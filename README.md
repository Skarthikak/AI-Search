git clone https://github.com/your-username/ai-search-engine.git
cd ai-search-engine
echo "# AI Search Engine" >> README.md
git init
git add README.md
git commit -m "Initial commit"
git push -u origin main
# AI Search Engine

This project is an AI search engine that fetches AI models from the Hugging Face Model Hub and AI news updates from NewsAPI.

## Setup

### Backend

1. Navigate to the `backend` directory:
   ```bash
   cd backend
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
pip install -r requirements.txt
python app.py
cd frontend
npm install
npm start

git add .
git commit -m "Initial setup for AI search engine"
git push origin main

