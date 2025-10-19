# AI Fitness Lead Categorizer 🧠💪

A simple **n8n automation** that uses **AI (OpenRouter)** to categorize incoming fitness leads, update a **Google Sheets CRM**, assign a coach, and send a **Gmail alert**.

---

## ⚙️ What It Does
- 🤖 Uses AI to label leads as: *Weight Loss*, *Muscle Gain*, *Nutrition Plan*, or *General Inquiry*  
- 📋 Adds results to Google Sheets  
- 🧑‍🏫 Auto-assigns a coach based on the category  
- 📧 Sends a Gmail email notification for each new lead  

---

## 🧩 Workflow Outline
- Manual Trigger  
- Mock Leads (sample data)  
- AI Categorizer (OpenRouter API)  
- Parse Category (extract AI output)  
- Merge (combine lead data + category)  
- Assign Coach (logic based on category)  
- Append to Google Sheets (CRM)  
- Gmail Notification (email summary)

---

## 🪄 Tech Stack
- **n8n** for workflow automation  
- **OpenRouter AI** (`mistralai/mistral-7b-instruct`) for categorization  
- **Google Sheets API** for CRM updates  
- **Gmail API** for notifications  

---

## 🧠 Example Output
| Name | Category | Coach |
|------|-----------|--------|
| Alice | Weight Loss | Coach A |
| Ben | Muscle Gain | Coach B |
| Cara | Nutrition Plan | Coach C |
| Dan | General Inquiry | Coach General |

---

## 🗂️ Workflow File
`ai_fitness_lead_categorizer_workflow.json` → import directly into n8n

---

MIT License © 2025 Jem
