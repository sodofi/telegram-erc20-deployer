# Telegram ERC20 Deployer

A monorepo containing a Telegram bot and mini-app for deploying ERC20 tokens.

## Setup

1. Install dependencies:
```bash
yarn install
```

2. Copy `.env.example` to `.env` and fill in the required environment variables.

3. Start the development servers:
```bash
# Start the bot
cd bot
yarn dev

# Start the mini-app
cd miniapp
yarn dev

# Start ngrok tunnel (in a separate terminal)
yarn tunnel
``` 