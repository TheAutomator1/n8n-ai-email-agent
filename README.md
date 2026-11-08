# n8n AI Email Agent

Reads your Gmail, decides what's important, replies to real emails, ignores spam, and sends you a Telegram summary.

## How to use
1. Download `ai_email_agent_workflow.json`
2. In n8n: open a blank workflow, click the canvas, press Ctrl+V (or Import from file)
3. Add your credentials:
   - Gmail IMAP: imap.gmail.com, port 993, Gmail app password
   - Groq API key (model: openai/gpt-oss-120b)
   - Telegram bot token + your chat ID
   - Gmail SMTP: smtp.gmail.com, port 465, same app password
4. In "Send Email", set From Email to your Gmail address
5. Publish

Video: [YOUTUBE LINK]
