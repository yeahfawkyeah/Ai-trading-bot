# Ai-trading-bot
Trading bot forex and crypto for educational purposes only

## ⚠️ Disclaimer
This is for educational purposes only. Trading is risky. Past performance does not guarantee future results.

## Features
- Real-time market analysis
- AI-powered trading signals
- Risk management tools
- Portfolio tracking
- Mobile app (Android)

## Tech Stack
- Frontend: React Native
- Backend: Node.js
- ML: TensorFlow
- Database: PostgreSQL
EOF

# Create .gitignore
cat > .gitignore << 'EOF'
node_modules/
.env
.env.local
*.log
.DS_Store
__pycache__/
*.pyc
build/
dist/
.vscode/
.idea/
EOF

# Initial commit
git add .
git commit -m "Initial project setup for AI trading bot"
