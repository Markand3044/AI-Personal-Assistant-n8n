# 🤖 AI Personal Assistant using n8n, Groq LLM & Google Workspace

An intelligent AI-powered Personal Assistant built with **n8n** that automates daily productivity tasks using **Large Language Models (LLMs)** and integrates with multiple Google services. The assistant can understand natural language requests, select the appropriate tool, execute the task, and return contextual responses.

This project demonstrates AI workflow orchestration, API integration, conversational memory, and intelligent automation using modern no-code/low-code technologies.

---

## 🚀 Features

- 🧠 AI-powered conversational assistant using Groq LLM
- 📅 Create, retrieve, and delete Google Calendar events
- 📧 Read and send Gmail messages
- 🌐 Perform real-time web searches using SerpAPI
- 📝 Create, update, and retrieve notes
- ✅ Create, view, and delete tasks
- 💰 Track daily expenses
- 🧠 Conversational memory for context-aware interactions
- 🔗 Webhook-based API interface for external applications
- ⚡ Modular workflow design for easy scalability

---

## 🏗️ System Architecture

```
                User
                  │
                  ▼
             Webhook Trigger
                  │
                  ▼
           AI Agent (Groq LLM)
                  │
      ┌───────────┼────────────┐
      │           │            │
      ▼           ▼            ▼
 Gmail API   Google Calendar  SerpAPI
      │           │            │
      ├───────────┼────────────┤
      ▼           ▼            ▼
 Notes       Task Manager   Expense Tracker
                  │
                  ▼
          Response to Webhook
```

---

## 🛠️ Tech Stack

| Category | Technologies |
|----------|--------------|
| Workflow Automation | n8n |
| Large Language Model | Groq LLM |
| APIs | Gmail API, Google Calendar API, SerpAPI |
| Communication | Webhooks |
| Data Storage | Google Sheets (Expense Tracking) |
| Productivity | Google Docs (Notes) |
| Authentication | OAuth 2.0 |
| Data Format | JSON |

---

## 📂 Workflow Overview

The workflow follows these steps:

1. User sends a request through a Webhook.
2. The AI Agent interprets the user's intent using Groq LLM.
3. Based on the request, the agent selects the appropriate tool.
4. The selected API executes the requested action.
5. Results are returned to the AI Agent.
6. The AI Agent generates a natural language response.
7. The response is sent back through the webhook.

---

## 🔧 Supported Functionalities

### 📅 Calendar Management
- Create events
- View events
- Delete events

### 📧 Gmail
- Read emails
- Send emails
- Retrieve specific messages

### 🌐 Web Search
- Search the web using SerpAPI
- Retrieve current information

### 📝 Notes
- Create notes
- Update notes
- Retrieve notes

### ✅ Task Management
- Create tasks
- View tasks
- Delete tasks

### 💰 Expense Tracking
- Add expenses
- Retrieve expense history

---

## 💬 Example Commands

```
Create a meeting tomorrow at 10 AM with Rahul.

Send an email to markand@example.com.

Search the latest AI news.

Show my meetings for today.

Create a task to complete my assignment.

Delete tomorrow's meeting.

Save this note:
Prepare resume for AI Labs interview.

Track an expense of ₹450 for dinner.
```

---


## 📁 Project Structure

```
AI-Personal-Assistant-n8n/
│
├── README.md ⭐
│
├── screenshots/
│   ├── workflow.png
│   ├── architecture.png
│   ├── gmail.png
│   ├── calendar.png
│   ├── notes.png
│   ├── tasks.png
│   ├── expense.png
│
└── demo.mp4 (or a YouTube/Loom link in the README)

---

## 📈 Skills Demonstrated

- AI Workflow Automation
- Prompt Engineering
- AI Agent Development
- Large Language Models (LLMs)
- REST API Integration
- Google Workspace Automation
- OAuth Authentication
- Conversational AI
- Workflow Orchestration
- Webhook Integration
- Modular Automation Design

---


## 👨‍💻 Author

**Markand Vyas**
