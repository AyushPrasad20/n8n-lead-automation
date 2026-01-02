# n8n Lead Automation

## Overview
This project contains a production-ready automation workflow built using n8n.
The workflow captures lead data via a webhook and stores it in Google Sheets.

## Workflow Steps
1. Webhook receives JSON lead data
2. Data is validated and parsed
3. Lead details are appended to Google Sheets
4. Workflow runs using a production webhook URL

## Sample Input Payload
```json
{
  "name": "John Doe",
  "email": "john@example.com",
  "requirement": "Need automation for lead tracking",
  "source": "Website"
}
