# Human-in-the-loop-AI-Content-Generator-n8n-Telegram-
This project demonstrates an AI-powered content automation workflow built with n8n, OpenAI, and Telegram, designed to keep humans in control of AI-generated outputs through an approval loop.
🚀 Project Overview

The automation receives a content topic from Telegram, generates a post using OpenAI, and sends it back to a human reviewer for approval.
If the content is rejected, it is automatically sent to another AI agent for regeneration until approval is granted.

This ensures quality, accuracy, and human oversight while maintaining automation efficiency.

🔁 Workflow Logic

Topic is submitted via Telegram

AI Agent (OpenAI) generates content

Content is sent to a human reviewer on Telegram

Reviewer response:

✅ Approve → Content is finalized and sent

❌ Decline → Content is routed to another AI agent for regeneration

Regenerated content is returned for re-approval (loop continues until approved)

🛠️ Tech Stack

n8n – Workflow automation

OpenAI – AI content generation

Telegram Bot API – User interaction & approval loop

Human-in-the-loop design – Quality assurance

✨ Key Features

Human approval before final output

Automated AI regeneration loop

Telegram-based interaction (simple and fast)

Modular and scalable workflow

Suitable for social media, marketing, and content teams

📌 Use Cases

Social media content approval

Marketing copy generation

Editorial workflows

AI-assisted communication systems

Any scenario requiring controlled AI output

📂 Repository Contents

workflow.json – Exported n8n workflow

README.md – Project documentation

.env.example – Environment variable template (API keys not included)

🔐 Environment Variables

Create a .env file and add:

OPENAI_API_KEY=your_openai_api_key
TELEGRAM_BOT_TOKEN=your_telegram_bot_token

▶️ How to Run

Install and run n8n

Import the workflow.json file

Configure credentials (OpenAI & Telegram)

Activate the workflow

Send a topic via Telegram to start

📈 Future Improvements

Content scoring before human review

Multi-language support

Platform auto-publishing (LinkedIn, Twitter, etc.)

Feedback-based fine-tuning

👤 Author
Muhammad Yunusa Badamasi
Data & Automation Enthusiast
AI • n8n • Workflow Automation
Muhammad Yunusa Badamasi
Data & Automation Enthusiast
AI • n8n • Workflow Automation
