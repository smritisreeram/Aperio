# Aperio: The Autonomous Research Discovery Agent 🛡️🔍

**Aperio** (Latin for *"to reveal"*) is an autonomous agentic system built with the **Google AI Agents ADK**. It is designed to combat "Passive Reading Syndrome" by transforming static research papers into a dynamic, two-way critical dialogue. 

Unlike standard AI summarizers that simplify content, Aperio **audits** it—uncovering methodological weaknesses, identifying knowledge gaps, and preparing students for academic defense.

## 🚀 Live Demo
**Service URL:** [https://adk-default-service-name-832916986400.us-central1.run.app/docs](https://adk-default-service-name-832916986400.us-central1.run.app/docs)

---

## ✨ Key Features

* **🛡️ Ethos (Integrity Audit):** A PRISMA-grounded check for sample size, selection bias, and statistical transparency.
* **🔥 Contra (The Adversary):** Identifies the "weakest link" in an argument and generates high-difficulty questions for thesis defense prep.
* **🔭 Gap-Finder (The Innovator):** Autonomously identifies "Knowledge Gaps" to suggest original research directions.
* **✈️ Paper-Pilot (The Navigator):** Structural breakdown of research into *Setup*, *Execution*, and *Outcome*.

---

## 🛠️ Technology Stack

* **Framework:** [Google AI Agent SDK (ADK)](https://github.com/google/ai-agents-adk) - Manages the autonomous planning loop and agentic persona.
* **LLM:** **Gemini 1.5 Flash** (via Vertex AI) - Utilized for high-speed inference and a massive context window for dense research analysis.
* **Deployment:** **Google Cloud Run** - Serverless, containerized hosting for global scalability.
* **Containerization:** **Docker** - Ensuring environment consistency from local to cloud.
* **Language:** Python 3.10+

---

## 🏗️ Architecture

Aperio moves beyond linear prompting by utilizing a **Reasoning Loop**:
1.  **Ingestion:** Scans methodology and results via Gemini 1.5 Flash.
2.  **Autonomous Planning:** The ADK identifies "Risk Areas" in the text.
3.  **Module Activation:** Dynamically triggers the Auditor, Adversary, or Innovator lenses.
4.  **Integrated Brief:** Delivers a 360-degree "Uncovered Truths" report.

---

## 💻 Local Setup

### Prerequisites
* Google Cloud Project with Vertex AI enabled.
* Python 3.10+
* Docker (optional, for containerization)

---

## 📄 License
This project is developed for the **Gen AI Academy APAC Edition Hackathon**.

**Developed by:** Smriti Sreeram
