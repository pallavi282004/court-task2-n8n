# Task 2 — n8n WhatsApp Automation

##  Workflow JSON
File: `task2-workflow.json`

##  What it does
- Connects WhatsApp API to court data service.
- Responds to specific commands from WhatsApp users.
- Sends back case details or order links.

##  Setup
1. Import the JSON into your n8n instance (Import → From File).
2. Add credentials for WhatsApp API and court data API in n8n.
3. Activate workflow.

##  Testing
- Send `/case 10145/2021` via WhatsApp.
- Workflow will reply with matching court data.

##  Known Issues
- Requires active n8n server.
- WhatsApp API must be approved for the number.

