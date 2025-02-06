## AI-Powered Email Reply Bot using n8n and DeepSeek Model v1

## Overview
This project sets up an AI-powered email response system using n8n as the workflow automation tool and DeepSeek Model v1 for generating intelligent replies. The AI Router Gemini is used to create the API key for seamless integration.

## Features
- Automated email replies using AI.
- Workflow automation with n8n.
- AI-driven responses using DeepSeek Model v1.
- Secure API key management via AI Router Gemini.

## Prerequisites
Before setting up the project, ensure you have:
- An n8n instance running (cloud/self-hosted).
- Access to DeepSeek Model v1.
- An API key from AI Router Gemini.

## Installation and Setup
### Step 1: Clone the Repository
```sh
git clone https://github.com/yourusername/n8n-ai-mailbot.git
cd n8n-ai-mailbot
```

### Step 2: Set Up n8n
1. Install n8n:
   ```sh
   npm install -g n8n
   ```
2. Start n8n:
   ```sh
   n8n
   ```
3. Access n8n via `http://localhost:5678`.

### Step 3: Configure AI Model
1. Get an API Key from AI Router Gemini.
2. Configure the DeepSeek Model v1 in n8n:
   - Create an HTTP Request node in n8n.
   - Use the API Key in the request headers.

### Step 4: Build the Workflow
1. Create a workflow in n8n.
2. Add an **Email Trigger** to capture incoming emails.
3. Use an **HTTP Request** node to connect with DeepSeek Model v1.
4. Parse the AI response and send an automated reply.

### Step 5: Deploy
Run the workflow and test by sending an email to trigger AI-generated responses.

## Usage
- Use this bot to automate email responses efficiently.
- Integrate with various email providers via n8n.

## License
This project is licensed under the MIT License.

## Contact
For issues or contributions, open an issue on GitHub or reach out at **manojkumargowd063@gmail.com**.

