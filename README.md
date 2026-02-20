# spidey.bot
🤖 n8n Telegram Character Bot

An AI-powered Telegram chatbot built using n8n and OpenAI, designed to simulate a fictional character persona through dynamic, real-time conversations.

This workflow demonstrates persona-based prompt engineering and LLM orchestration using low-code automation.

🚀 Overview

The Telegram Character Bot allows users to interact with an AI that stays fully in character while responding naturally to messages.

The system uses:

Telegram Bot API for user interaction

OpenAI language model for character-based responses

n8n for workflow automation and orchestration

✨ Features

🎭 Persona-driven conversational AI

📲 Real-time Telegram interaction

🧠 Prompt-engineered character consistency

⚡ Automated workflow using n8n

🔁 Scalable to support multiple characters

🏗️ Architecture

Telegram → n8n Workflow → OpenAI Model → Telegram Response

Workflow Components

Telegram Trigger Node
Listens for incoming user messages.

AI Agent Node
Applies system prompt to enforce character persona.

OpenAI Chat Model Node
Generates natural language responses.

Telegram Send Message Node
Sends the AI-generated response back to the user.

🛠️ Tech Stack

n8n (Workflow Automation Platform)

OpenAI GPT Model (gpt-5-mini or configurable)

Telegram Bot API

Prompt Engineering

📂 How It Works

User sends a message to the Telegram bot.

The message is passed into the AI Agent.

A system prompt enforces strict character behavior.

OpenAI generates a persona-consistent response.

The response is returned to the user via Telegram.

🎯 Use Cases

Character-based conversational AI demos

Prompt engineering experimentation

AI persona simulation

LLM workflow automation projects

Portfolio project for showcasing AI integration

🔧 Setup Instructions
1️⃣ Prerequisites

n8n (Cloud or Self-Hosted)

Telegram Bot Token

OpenAI API Key

2️⃣ Import the Workflow

Open n8n

Navigate to Workflows

Click Import

Paste the workflow JSON

Save

3️⃣ Configure Credentials

Connect Telegram credentials

Add OpenAI API key

Activate the workflow

🔐 Security Notes

API credentials are not included in this repository.

Store API keys securely in n8n’s credential manager.

Do not commit sensitive information to version control.

📈 Future Improvements

Multi-character switching via commands

Persistent conversation memory

Context window management

Character customization dashboard

Web interface support

👨‍💻 Author

Built using n8n and OpenAI to demonstrate persona-driven AI automation workflows.
