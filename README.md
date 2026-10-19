# AI Shopping Assistant on Telegram

An AI-powered shopping assistant built using n8n that helps users discover relevant products through Telegram text and voice queries.

## Features

- Accepts shopping queries through Telegram.
- Supports text and voice-based shopping requests.
- Retrieves Amazon product information using ScraperAPI.
- Recommends the five most relevant products based on user requirements.
- Provides personalized styling recommendations based on user preferences.
- Automates the shopping assistance workflow using AI.

## Tech Stack

- **Workflow Automation:** n8n
- **Messaging Platform:** Telegram Bot API
- **AI Model:** Google Gemini
- **Product Data Retrieval:** ScraperAPI
- **Version Control:** GitHub

## Workflow Architecture

Telegram Trigger → AI Agent (Gemini) → ScraperAPI Product Retrieval → Telegram Response

## Setup

1. Import `ai-shopping-assistant-telegram.json` into your n8n instance.
2. Configure your Telegram bot credentials in n8n.
3. Configure your Gemini model credentials.
4. Configure ScraperAPI credentials and verify the relevant product retrieval settings.
5. Test the workflow and activate it.

## Security

API keys, bot tokens, and other secrets are not included in this repository. Configure credentials securely in n8n.

## Author

Developed as an AI-powered workflow automation project using n8n and Telegram.
