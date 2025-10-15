# ${{ values.agentName }}

This repository defines a watsonx Orchestrate agent using the **Agent Development Kit (ADK)**.

## 🧠 Agent info
- **Name:** ${{ values.agentName }}
- **Description:** ${{ values.description }}
- **LLM:** ${{ values.llmModel }}

## 🚀 Quick start
To import this agent into your local Orchestrate Developer Edition:
```bash
pip install ibm-watsonx-orchestrate
orchestrate env add -n local -u http://localhost:8080 --type mcsp --activate
orchestrate agents import -f agent.yaml