# Sigma_Chatbot – My First AI-Powered Financial Sidekick

## Overview
Sigma is a Python-based, rule-driven chatbot designed to assist users with basic cryptocurrency investment decisions. It evaluates predefined data on profitability and sustainability, providing simple, friendly advice.

## Features
- Conversational, approachable chatbot personality.
- Analyzes price trends, market capitalization and energy usage.
- Recommends cryptocurrencies based on sustainability or profitability.
- Basic natural language understanding using rule-based logic.

## How It Works
Sigma uses straightforward `if-else` logic to interpret user questions about trending or sustainable cryptocurrencies. It simulates AI decision-making by matching user intent to preset rules and data.

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
```

## Example Conversation

**User:** What's the most sustainable coin?  
**Sigma:** Cardano is a great choice! It’s eco-friendly and has strong long-term potential.

**User:** Which crypto is trending up?  
**Sigma:** Bitcoin and Cardano are currently rising!

## Disclaimer
Crypto is risky- always do your own research!

## Files
- `Sigma_Chatbot.ipynb`
- `sigma_chatbot.py`
- `README.md`