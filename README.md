# 🤖 HR Automation Workflow using n8n

An AI-powered HR automation workflow built with **n8n** to streamline resume screening and candidate evaluation. The workflow automates the initial recruitment process by parsing resumes, extracting candidate information, and generating structured outputs for further analysis.

## 📌 Overview

Recruiters often spend significant time manually reviewing resumes. This workflow automates the initial screening stage by processing uploaded resumes and extracting relevant candidate details, reducing manual effort and improving consistency.

## ✨ Features

- 📄 Resume parsing from uploaded documents
- 🤖 AI-powered information extraction
- 👤 Candidate details extraction
- 💼 Skills and experience identification
- 📊 Structured JSON output
- ⚡ Fully automated workflow using n8n

## 🛠️ Built With

- **n8n** – Workflow Automation
- AI/LLM Nodes
- HTTP Request Nodes
- JSON Processing
- File Processing


## 🚀 Getting Started

### Import into n8n

1. Download `HR Resume.json`
2. Open your n8n instance.
3. Click **Import from File**.
4. Select the workflow JSON.
5. Configure the required credentials and API keys.
6. Execute the workflow.

## ⚙️ Requirements

Depending on your configuration, you may need:

- n8n (latest version recommended)
- AI model credentials (OpenAI, Gemini, Cohere, etc.)
- Any external APIs used in the workflow

## 📈 Workflow

The workflow performs the following steps:

1. Accepts a resume as input.
2. Extracts resume content.
3. Sends the content to an AI model.
4. Parses candidate information.
5. Produces structured output for downstream HR processes.

## 📸 Workflow Preview


Example:

```
<p align="center">
  <img width="900" alt="Workflow" src="https://github.com/user-attachments/assets/e94cb1ae-cb97-44d9-bd16-11c816c214a5" />
</p>
```

## 🔒 Notes

- API keys and credentials are **not included** in the exported workflow.
- Configure your own credentials before execution.

## 📄 License

This project is available for educational and portfolio purposes.

---

**Author**

**Fatima Azfar**

- BS Computer Science, NED University of Engineering & Technology
- AI & Automation Enthusiast
- LinkedIn: https://www.linkedin.com/in/fatimaazfar/
