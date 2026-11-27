# AI Follow-up Agents and AI Employee

At **Abhaya International**, customer and internal follow-ups depended on staff being available, so responses lagged. I built **AI agents** that plan a task, use business tools like email, WhatsApp, Google Sheets and the CRM, check the result and keep going around the clock. Together they work as an **AI employee** that handles routine desk work every day.

> The source code is not public. This repository documents how the system works. A live walkthrough is available on request.

## Result

Response time cut by **about 60%**, with follow-ups running 24/7 without manual input.

## What the agents do

- Send follow-ups to customers and internal teams on time
- Update reports and sheets
- Assign new leads to the right person
- Send reminders for pending work
- Log every action so the team can review it

## How it works

```
          +------------------------------+
          |          AI agent            |
          |   plan  ->  act  ->  check   |
          +------------------------------+
            |       |        |        |
          Email  WhatsApp  Sheets    CRM
            |       |        |        |
          +------------------------------+
          |  Action log for human review |
          +------------------------------+
```

## Related work

- **LLM business assistant:** answers team questions, drafts replies and summarises reports in plain language (OpenAI and Gemini APIs)
- **RAG knowledge search:** answers questions from company SOPs and documents, with the source document shown for each answer

## Tech stack

AI agents, LLMs (OpenAI and Gemini APIs), RAG, Python, Google Apps Script, Gmail, WhatsApp messaging, Google Sheets, Zoho CRM

## My role

I designed the agent workflows, connected them to the business tools and rolled them out with the teams that use them.

## Author

**Saurabh Kumar Sharma**, Automation Specialist  
[Portfolio](https://mrsaurabhkumarsharma.github.io) · [LinkedIn](https://www.linkedin.com/in/saurabh-sharma-7aa432416) · mrsaurabhkumarsharma@gmail.com
