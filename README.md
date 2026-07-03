# 💧 AquaSentinel AI

> **An Agentic AI System for Intelligent Water Safety, Purification Guidance, Water Conservation, and Automated Complaint Registration.**

![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Platform](https://img.shields.io/badge/Built%20With-n8n-orange)
![AI](https://img.shields.io/badge/AI-Multi--Agent-blue)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 📖 Overview

AquaSentinel AI is an intelligent multi-agent system designed to help citizens make informed decisions about water quality and safety.

Instead of relying on a single chatbot, AquaSentinel uses specialized AI agents coordinated by a central AI Manager. Each agent is responsible for a specific domain such as water safety, purification, conservation, or complaint registration, ensuring accurate, focused, and actionable responses.

---

## ❗ Problem Statement

Millions of people face water-related issues such as:

- Unsafe or contaminated drinking water
- Confusion about selecting the right water purifier
- Water wastage due to poor conservation practices
- Difficulty reporting municipal water issues

Existing solutions are often fragmented, requiring users to consult multiple sources.

AquaSentinel brings these services together into one intelligent platform.

---

## 💡 Solution

AquaSentinel combines multiple AI specialists into a single coordinated system capable of:

- Assessing common water safety issues
- Recommending suitable purification methods
- Promoting water conservation practices
- Simplifying complaint registration through an automated workflow

The AI Manager routes each user query to the most appropriate specialist, ensuring concise and relevant responses.

---

## ✨ Key Features

- 🛡️ Water Safety Assessment
- 💧 Water Purification Guidance
- 🌱 Water Conservation Advisor
- 📝 Automated Complaint Registration
- 🤖 Multi-Agent AI Architecture
- ⚡ Intelligent Tool Routing
- 📧 Complaint ID & Email Confirmation
- ☁️ Cloud-based n8n Workflow

---
##  🏗️ System Architecture

```
                User
                  │
                  ▼
        AquaSentinel AI Manager
                  │
      ┌───────────┼────────────┐
      ▼           ▼            ▼
 Water Safety  Water         Water
   Advisor   Purification  Conservation
                Advisor       Advisor
                  │
                  ▼
        Complaint Registration
                  │
                  ▼
          n8n Complaint Form
```

The AI Manager intelligently routes each user request to the appropriate specialist AI agent. If multiple domains are involved, it combines the responses into a single concise answer.

## ⚙️ Tech Stack

| Component           |      Technology               |
|---------------------|-------------------------------|
| Workflow Automation | n8n                           |
| AI Orchestration    | Multi-Agent AI                |
| LLM                 | Gemini 2.5 Flash / Groq Llama |
| Complaint Form      | n8n Form                      |
| Memory              | Simple Memory                 |
| Deployment          | n8n Cloud                     |
| Version Control     | GitHub                        |

## 🤖 AI Specialists

AquaSentinel uses four specialized AI agents coordinated by a central AI Manager.

### 🛡️ Water Safety Advisor
- Detects common water quality issues
- Assesses potential health risks
- Provides practical safety recommendations

### 💧 Water Purification Advisor
- Explains TDS and water treatment
- Recommends suitable purifiers
- Suggests purification methods

### 🌱 Water Conservation Advisor
- Promotes sustainable water usage
- Recommends conservation techniques
- Encourages efficient household practices

### 📝 Complaint Registration Advisor
- Guides users to the official complaint form
- Explains required information
- Generates complaint submission guidance

## 🔄 Workflow

The AquaSentinel workflow follows a multi-agent architecture:

1. User submits a water-related query.
2. AI Manager analyzes the request.
3. The appropriate specialist AI agent(s) are selected.
4. Specialist agents generate domain-specific recommendations.
5. If required, the Complaint Registration Agent directs the user to the official complaint form.
6. The AI Manager combines the responses into a single concise answer.

## 📁 Project Structure

```
AquaSentinel-AI/
│
├── workflow/
│   └── AquaSentinel_AI_Workflow.json
│
├── screenshots/
│
├── docs/
│
├── assets/
│
├── README.md
├── LICENSE
└── .gitignore
```
## 📸 Screenshots

### AI Workflow

> *(Insert workflow screenshot here)*

### Chat Interface

> *(Insert chatbot conversation screenshot here)*

### Complaint Registration Form

> *(Insert complaint form screenshot here)*

## 🚀 Getting Started

### Prerequisites

- n8n Cloud or Self-hosted n8n
- Gemini API Key or Groq API Key

### Installation

1. Clone this repository.
2. Import the workflow JSON into n8n.
3. Configure the required API credentials.
4. Activate the workflow.
5. Start chatting with AquaSentinel AI.

## 🔮 Future Scope

- IoT sensor integration for real-time water monitoring
- GIS-based water issue mapping
- Multilingual support
- Mobile application
- Predictive water quality analytics
- Integration with municipal water departments

## 👨‍💻 Author

**Pratham Deshmukh**

- GitHub: https://github.com/prathamdesh07-afk
- LinkedIn:

## 🙏 Acknowledgements
This project was developed as part of an AI Hackathon to demonstrate the potential of Agentic AI for solving real-world water management challenges using n8n automation and Large Language Models.
