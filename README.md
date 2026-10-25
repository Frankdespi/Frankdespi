# Franklin Madumere

**AI workflows that know when to ask a person.**

I build n8n and Make.com automations that use OpenAI to score, route, and log work. I spent more than 15 years in regulated banking operations at Fidelity Bank Plc in Lagos, Nigeria, so I build with limits, reviews, and records from the start.

[Portfolio site](https://frankdespi.github.io) · [LinkedIn](https://linkedin.com/in/franklinmadumere) · [frankdespi@gmail.com](mailto:frankdespi@gmail.com)

## Featured project

### [Reputation & Feedback Intelligence Engine](https://github.com/Frankdespi/reputation-feedback-intelligence-engine)

Two connected n8n workflows that turn a customer feedback form into a scored, routed, and logged case. This was my capstone for the TS Academy AI & Automation program, built around a car care chain case study with sample data.

- OpenAI scores each reply for sentiment, severity, and confidence.
- Uncertain results go to a person instead of being acted on.
- AI-drafted replies are saved for review and are never sent automatically.
- Severe or repeat complaints alert a manager on Telegram and by email.
- Every outcome is written to a log with its score, route, and timestamp.

## Also built

### [Sales & Inventory Automation](https://github.com/Frankdespi/Frankdespi.github.io/tree/main/projects/sales-inventory-automation)

A small juice business was tracking everything by hand. Now the owner logs sales, batches, and costs in Google Sheets, the spreadsheet does the arithmetic, and n8n does the watching, in six lanes on one canvas.

- A Telegram alert when a flavour or its stickers run low.
- An 8 pm summary by Telegram and email: bottles sold, revenue, top seller, and which flavours and sizes were sold.
- A 6 pm nudge if nothing has been logged yet.
- A Sunday roll-up of revenue, costs, profit, and flavours sold, saved to the sheet and sent to the owner by Telegram and email.
- An error alert, and a weekly backup to Google Drive.

Built with n8n, Google Sheets, Telegram, Gmail, and Google Drive.

### [My First AI Agent](https://github.com/Frankdespi/Frankdespi.github.io/tree/main/projects/first-ai-agent)

An n8n AI agent that takes one Telegram prompt, searches the web, then messages and emails me the answer. The main lesson: an agent will not chain tools on its own, so the system prompt has to say "search first, then email the result."

Built with n8n's AI Agent node, an OpenAI chat model, Simple Memory, SerpApi, Gmail, and Telegram.

## What I work with

| Area | Tools |
| --- | --- |
| Automation | n8n (workflows and AI agents), Make.com |
| AI | OpenAI API, Claude |
| Data and messaging | Google Sheets, Gmail, Google Forms, Google Drive, Telegram Bot API, SerpApi |
| Scripting | JavaScript for n8n Code nodes (written and debugged with Claude), JSON |
| Cloud | AWS, CloudFormation, Docker, Terraform (bootcamp practice) |

## Smaller builds

- **HR applicant tracking pipeline (n8n):** a multi-node workflow that connects Gmail and Google Sheets.
- **Telegram weather alert bot (n8n):** sends weather notifications to a Telegram chat through a bot.
- **Google Sheets integrations (Make.com):** scenarios that include the OAuth setup, plus fixes for authentication and sheet-name errors.

## Credentials

- AWS Certified Solutions Architect – Associate (June 2025)
- AWS Certified Cloud Practitioner (January 2025)
- Postgraduate Program in Cloud Computing, Great Lakes Executive Education (December 2023)
- AI & Automation Program, TS Academy (May to October 2026)

## A note on data

The capstone project uses sample data. For the sales and inventory automation, the business name and its figures are kept private. Nothing from my employer or its customers appears in any repository.
