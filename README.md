# 🏥 Healthcare AI Agent (Python + Parlant SDK)

A **Healthcare Conversational AI Agent** built using the **Parlant SDK** and **async Python workflows**.  
This project demonstrates how to design **structured conversational journeys** for real-world **healthcare automation**, including **appointment scheduling, lab results, and insurance inquiries**.

---

## 🚀 Features

- 📅 **AI Appointment Scheduling**
  - Fetches upcoming slots (`get_upcoming_slots`)
  - Handles fallback scheduling with later slots (`get_later_slots`)
  - Confirms and books appointments with patients (`schedule_appointment`)

- 🧪 **AI Lab Results Assistant**
  - Retrieves lab results (`get_lab_results`)
  - Explains results empathetically while deferring medical advice
  - Safety-first guidelines for “good”, “bad”, or “unavailable” results

- 📖 **Healthcare Domain Glossary**
  - Consistent terms like **Office Hours**, **Insurance Providers**, and **Doctor Profiles**
  - Synonym support (e.g., “Professor X” → Charles Xavier)

- 🛡️ **Guidelines & Safety Controls**
  - Redirects urgent cases to call the office
  - Handles insurance-related queries
  - Politely declines off-topic conversations

- 🔀 **Disambiguation**
  - Smartly routes between **Scheduling Journey** and **Lab Results Journey** when patient intent is unclear

---

## ⚙️ Tech Stack

- **Language:** Python 3.10+  
- **Framework:** [Parlant SDK](https://www.parlant.ai)  
- **Core Concepts:** Async tools, Journeys, Glossary, Guidelines, Disambiguation  
- **Paradigm:** Conversational AI, Dialog Management, Healthcare Automation  

---
