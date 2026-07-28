# 🤖 AI Lead Qualifier & CRM Auto-Responder

> **Production-ready automation scenario built in Make.com integrating Google Gemini AI, Webhooks, Google Sheets, and Gmail for automated lead scoring and multi-channel routing.**

---

## 📌 Problem Overview
Inbound sales leads often take hours or days to be manually evaluated and routed, resulting in lost deals and delayed response times. This automation pipeline ingests incoming lead submissions in real-time, leverages LLM intelligence to evaluate intent and budget fit, categorizes the lead status, updates a central Google Sheets CRM, and dispatches a personalized email response instantly.

---

## 🛠️ Tech Stack & Integrations
* **Automation Engine:** [Make.com](https://www.make.com/)
* **AI / LLM Processing:** Google Gemini API (`gemini-1.5-flash` / `gemini-2.0-flash`)
* **Trigger / Data Source:** Custom HTTP Webhook / Web Forms
* **CRM / Database:** Google Sheets API
* **Communication Channel:** Gmail API
* **Data Processing:** Regular Expressions (Regex), Dynamic String Manipulation (`trim`, `substring`), JSON Parsing
* **Reliability Features:** Rate-limit Error Handling (Sleep/Retry loops for HTTP 429 quota backoffs)

---

## ⚙️ Workflow Architecture & Process Flow
