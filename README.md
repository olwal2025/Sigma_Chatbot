# Sigma_Chatbot- My First AI-Powered Financial Sidekick!

## Overview
Sigma is a rule-based chatbot built using Python that helps users make simple cryptocurrency investment decisions. It analyzes predefined data for profitability and sustainability while offering advice accordingly.

## Features
- Friendly chatbot personality.
- Analyzes trends, market cap and energy usage.
- Recommends cryptos based on sustainability or profitability.
- Basic natural language understanding.

## How It Works
The chatbot uses `if-else` logic to respond to user queries about trending and sustainable cryptocurrencies. It mimics AI decision-making by matching user intent with predefined rules and data points.

## Sample Dataset

```python
crypto_db = {
    "Bitcoin": {
        "price_trend": "rising",
        "market_cap": "high",
        "energy_use": "high",
        "sustainability_score": 3/10
    },
    "Ethereum": {
        "price_trend": "stable",
        "market_cap": "high",
        "energy_use": "medium",
        "sustainability_score": 6/10
    },
    "Cardano": {
        "price_trend": "rising",
        "market_cap": "medium",
        "energy_use": "low",
        "sustainability_score": 8/10
    }
}

Example Conversation
You: What's the most sustainable coin?
CryptoBuddy: Invest in Cardano! It’s eco-friendly and has long-term potential!

You: Which crypto is trending up?
CryptoBuddy: Bitcoin and Cardano are rising!

Disclaimer
Crypto is risky — always do your own research!

Files
Sigma_Chatbot.ipynb
README.md


