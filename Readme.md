# AI Customer Ticket Routing Automation

## Overview

AI Customer Ticket Routing Automation is an academic prototype built using **n8n** and **Large Language Models (LLMs)** to automate customer ticket processing.

The workflow receives customer messages, extracts relevant information, enriches customer context, analyzes message content using AI, and routes tickets to the appropriate handling path.

## Project Objectives

- Automate customer message processing.
- Classify customer sentiment and inquiry categories.
- Assess ticket priority using AI.
- Retrieve customer information to enrich ticket context.
- Route tickets to relevant teams.
- Store ticket information and processing results for tracking.

## Workflow Architecture

The automation consists of the following stages:

1. **Input:** Receives customer messages through Telegram and Webhook triggers.
2. **Data Normalization:** Extracts and structures incoming message information into a consistent format.
3. **Customer Context Enrichment:** Looks up customer records using Google Sheets.
4. **AI Analysis:** Uses an LLM through OpenRouter to analyze customer messages and generate structured results.
5. **Decision & Routing:** Directs tickets according to their category and analysis results.
6. **Notifications:** Sends notifications through Telegram or email, depending on the workflow path.
7. **Data Persistence:** Stores ticket details and processing results in Google Sheets and supports ticket status tracking.

## Key Capabilities

- Customer message analysis.
- Sentiment classification.
- Inquiry category identification.
- AI-assisted priority assessment.
- Customer information lookup.
- Automated ticket routing.
- Notification automation.
- Ticket logging and status tracking.

## Technologies Used

- **n8n** – Workflow automation.
- **OpenRouter** – LLM integration.
- **Large Language Models (LLMs)** – Message understanding and classification.
- **Google Sheets** – Customer lookup and ticket records.
- **Telegram Bot API** – Message input and notifications.
- **Gmail** – Email notifications.

## Project Scope

This project was developed as an academic automation prototype to demonstrate the integration of AI analysis with workflow automation.

It was tested as a prototype and is not presented as a production deployment or as a system connected to a live company's customer database.

## Security & Data Privacy

Any publicly shared workflow configuration or screenshots should exclude API keys, credentials, private identifiers, customer information, and other sensitive data.

## Project Demonstration

Workflow screenshots and sanitized configuration examples can be added to this repository to illustrate the automation process.
