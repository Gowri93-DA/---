# AI-Powered Data Analysis Email Agent (n8n + Gemini + Google Sheets)

## Overview
This project demonstrates how Generative AI, BI, and workflow automation can work together to deliver instant business insights.

Instead of manually exploring dashboards, users can ask questions in chat, and an AI agent automatically analyzes the dataset and sends structured insights via email.

This project uses the July Onyx Data Challenge dataset.

---

## Problem Statement
Traditional dashboards require users to manually explore data to find answers.  
Business users often need quick answers without opening BI tools.

This solution automates the entire analytics process:
Chat question → AI analysis → Email insights

---

## Solution Workflow
1. User asks a question in chat
2. AI Agent interprets the query
3. Workflow fetches data from Google Sheets
4. AI analyzes the dataset
5. Structured insights are generated
6. Insights are automatically sent via Gmail

---

## Architecture
Chat Trigger → AI Agent (Google Gemini) → Google Sheets → AI Analysis → Gmail → Email with insights

---

## Tech Stack
- Power BI – Initial dashboard and data exploration
- n8n – Workflow automation
- Google Gemini AI – Natural language analysis
- Google Sheets – Dataset storage
- Gmail API – Automated email delivery

---

## Features
- Fully automated analytics workflow
- Natural language query support
- AI-generated business insights
- Structured, executive-ready email output
- No manual analysis required

---

## Example Use Case
User question:
"Compare customer satisfaction between groups"

Automated email output includes:
- Summary
- Key insights
- Recommended visualization
- Conclusion

---

## Repository Contents


/screenshots
    [workflow.png](https://github.com/Gowri93-DA/---/blob/main/Data%20Analysis%20Automation.png)
    [email_output.png](https://github.com/Gowri93-DA/---/blob/main/Data%20Analysis%20Automation.png)

README.md

---

## How to Run

1. Install n8n
2. Import the workflow JSON file
3. Connect:
   - Google Sheets credentials
   - Gmail credentials
   - Gemini API
4. Run workflow
5. Ask a question in chat

Insights will be sent automatically via email.

---

## Business Value
This solution demonstrates how AI can automate analytics workflows and reduce manual reporting effort.

It enables faster decision-making and improves accessibility of data insights for business users.

---

## Future Improvements
- Automated chart generation
- Slack / Teams integration
- PDF report generation
- Database integration (SQL)

