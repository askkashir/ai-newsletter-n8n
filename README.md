# n8n AI Newsletter

This project is an automated newsletter workflow built with **n8n**.  
It fetches the latest news, summarizes it using **Google Gemini**, and sends the summary to your email through **Gmail**.

## How it Works
1. **HTTP Request** → Fetches news from an API  
2. **AI Agent (Gemini)** → Summarizes the news  
3. **Set Node** → Prepares subject & message  
4. **Gmail Node** → Sends the email newsletter  

## Setup
1. Import `workflow.json` into your n8n instance.  
2. Add your **Gemini API Key** in n8n credentials.  
3. Connect your **Gmail account** in n8n credentials.  
4. Execute the workflow.  

## Notes
- API keys and Gmail credentials are **not included** in the exported workflow (for security).  
- You need to set up your own credentials in n8n to make it work.  

---
