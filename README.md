# Multi-Agent Research System

> An autonomous multi-agent AI system that performs end-to-end research by intelligently searching the web, extracting relevant information, synthesizing structured reports, and critically evaluating its own outputs using Large Language Models.

<p align="center">

![Python](https://img.shields.io/badge/Python-3.11-blue)
![LangChain](https://img.shields.io/badge/LangChain-Agentic%20AI-green)
![LLM](https://img.shields.io/badge/LLM-Gemini%20%7C%20OpenAI-orange)
![License](https://img.shields.io/badge/License-MIT-red)

</p>

---

## Overview

Conducting high-quality research manually involves multiple repetitive steps—searching different sources, filtering unreliable information, reading articles, organizing notes, writing reports, and verifying conclusions.

This project automates the entire workflow using a team of collaborative AI agents.

Instead of behaving like a simple chatbot, the system decomposes research into specialized tasks executed by multiple agents that work together to generate comprehensive, structured, and reliable research reports.

---

# Features

* 🔍 Autonomous Web Research
* 🤖 Multi-Agent Collaboration
* 🌐 Live Web Search using Tavily
* 📄 Intelligent Web Scraping
* 🧠 LLM-based Report Generation
* ✅ Self-Critique & Report Evaluation
* 📑 Structured Markdown Reports
* 💬 Interactive Streamlit Interface
* ⚡ Modular Agent Architecture
* 🔄 Extensible Tool Calling Framework

---

# System Architecture

```text
                User Query
                     │
                     ▼
            Research Planner Agent
                     │
     ┌───────────────┼───────────────┐
     ▼               ▼               ▼
 Search Agent   Scraper Agent   Knowledge Agent
     │               │               │
     └───────────────┼───────────────┘
                     ▼
           Report Generation Agent
                     │
                     ▼
          Evaluation / Critic Agent
                     │
                     ▼
           Final Research Report
```

---

# Agent Responsibilities

### 🔎 Research Agent

* Understands the research objective
* Plans search strategy
* Coordinates downstream agents

---

### 🌐 Search Agent

* Searches the web using Tavily
* Retrieves reliable resources
* Filters irrelevant information

---

### 📄 Content Extraction Agent

* Scrapes webpages
* Cleans extracted content
* Removes unnecessary HTML elements

---

### 📝 Report Generation Agent

* Summarizes findings
* Synthesizes information
* Produces structured reports

---

### ✅ Evaluation Agent

* Reviews generated reports
* Identifies factual inconsistencies
* Suggests improvements
* Improves report quality through iterative refinement

---

# ⚙️ Tech Stack

## Languages

* Python

## LLM Frameworks

* LangChain

## Models

* Google Gemini
* OpenAI GPT (configurable)

## Search

* Tavily Search API

## Web Scraping

* BeautifulSoup
* Requests

## Frontend

* Streamlit

## Utilities

* dotenv
* Markdown
* JSON

---

# 📂 Project Structure

```bash
MULTI-AGENT-RESEARCH-SYSTEM/

│── agents/
│── tools/
│── prompts/
│── utils/
│── app.py
│── config.py
│── requirements.txt
│── README.md
```

---

# Workflow

1. User submits a research query.
2. Planner agent creates a research strategy.
3. Search agent gathers relevant resources.
4. Scraper agent extracts webpage content.
5. LLM synthesizes information.
6. Evaluation agent critiques the generated report.
7. Final structured report is returned.

---

# Example Queries

* Latest advancements in Multimodal LLMs
* Explain Retrieval-Augmented Generation
* Compare LangGraph and CrewAI
* Research Quantum Machine Learning
* Future of Agentic AI
* State of Telugu Large Language Models

---

# Key AI Concepts Demonstrated

* Multi-Agent Systems
* Agent Orchestration
* Tool Calling
* Retrieval-Augmented Generation (RAG)
* Prompt Engineering
* LLM Reasoning
* Autonomous AI Workflows
* AI Planning
* Report Synthesis
* Self-Evaluation Pipelines

---

# Future Improvements

* Memory-enabled agents
* Multi-document retrieval
* Vector database integration
* Human-in-the-loop review
* Multi-modal document understanding
* PDF and research paper ingestion
* Async agent execution
* Local LLM support
* Citation-aware report generation

---

# Contributing

Contributions, feature requests, and suggestions are welcome.

Feel free to fork the repository and submit a pull request.

---

## 👨‍💻 Author

**Harishwar Chinikeri**

B.Tech, Computer Science and Engineering
National Institute of Technology Durgapur

**Interested in:** Generative AI • Agentic AI • LLM Research • NLP • MLOps
