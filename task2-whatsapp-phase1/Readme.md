# WhatsApp Lead-to-Booking Automation – Phase 1

## Project Overview

This project is the first phase of a WhatsApp Lead-to-Booking Automation system for a dental clinic. The goal is to design the chatbot conversation flow, prepare bilingual bot messages (English & Arabic), and connect the Twilio WhatsApp Sandbox with n8n using a webhook.

## Objective

- Design a complete WhatsApp conversation flow.
- Create bot message scripts in English and Arabic.
- Connect Twilio WhatsApp Sandbox to n8n via webhook.
- Verify that incoming WhatsApp messages are successfully received in n8n.

## Technologies Used

- n8n
- Twilio WhatsApp Sandbox
- ngrok (Static Domain)
- GitHub
- Mermaid / Flow Diagram

## Folder Structure

```
task2-whatsapp-phase1/
│
├── assets/
│   ├── flow-diagram.png
│   ├── messages.md
│   ├── n8n-workflow.png
│   ├── twilio-whatsapp-sandbox.png
│   └── workflow.png
│
├── workflow.json
└── README.md
```

## Screenshots

The `assets` folder contains screenshots of:

- WhatsApp Sandbox configuration
- n8n workflow
- Webhook execution
- Conversation flow diagram

## How the Webhook Works

1. A user sends a message to the Twilio WhatsApp Sandbox.
2. Twilio forwards the message to the public ngrok webhook URL.
3. The webhook is connected to an n8n workflow.
4. n8n receives the incoming message and processes the request.
5. The webhook connection is successfully verified through the workflow execution.

## Project Status

✅ Conversation flow completed

✅ Bot message scripts completed

✅ Twilio WhatsApp Sandbox configured

✅ n8n webhook connected

✅ GitHub repository created

## Author

**Ifra Malik**

BS Information Technology

GitHub: https://github.com/ifra489
