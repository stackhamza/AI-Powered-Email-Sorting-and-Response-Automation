# 📧 Email Classifier – n8n AI Automation Workflow  

> **Intelligently Classify, Organize, and Draft Responses for Incoming Emails**  

---

## 🚀 Overview  

The **Email Classifier Workflow** is an advanced **AI-powered automation** built using **n8n** that automatically classifies incoming emails, organizes them into predefined categories, and generates AI-drafted responses ready for review and sending.  

This automation saves time, improves communication efficiency, and ensures that every email receives the appropriate attention based on its category.  

---

## 🧩 Workflow Structure  

The automation follows this logical sequence:  

1. **Gmail Trigger:**  
   - The workflow is activated automatically whenever a new email is received in your Gmail inbox.  

2. **Email Classifier (AI):**  
   - The AI analyzes the incoming email content and identifies the correct category based on its context.  

3. **Categorization via Labels:**  
   - Depending on the detected category, the email is assigned to one of the following Gmail labels:  
     - 🟥 **Priority**  
     - 🟩 **Support**  
     - 🟨 **Promotion**  
     - 🟦 **Finance / Billing**  

4. **AI Response Draft:**  
   - Once the email is categorized, a corresponding **AI Agent** generates a **draft response** in Gmail.  
   - The draft email is automatically created in the respective category’s section for manual review and approval before sending.  

---

## 🧠 Logic Summary  

- The workflow starts when a **new email** arrives.  
- The **Email Classifier node** determines the message type using AI text understanding.  
- The system applies the appropriate **label** in Gmail.  
- The corresponding **AI Agent** (Support, Priority, Promotion, or Finance/Billing) generates a relevant **draft reply**.  
- You can review, edit, and send the AI-generated draft email from Gmail directly.  

---

## 🗂️ Email Categories  

| Category | Description | Action Taken |
|-----------|--------------|--------------|
| **Priority** | High-importance or urgent messages | AI drafts a quick priority response |
| **Support** | Customer queries and complaints | AI drafts customer support reply |
| **Promotion** | Marketing or promotional offers | AI drafts promotional acknowledgment |
| **Finance / Billing** | Invoices, payments, or account details | AI drafts finance-related response |

---

## ⚙️ Workflow Components  

| Component | Function |
|------------|-----------|
| **Gmail Trigger** | Activates workflow on new email arrival |
| **Email Classifier Node** | Analyzes content to determine email type |
| **Switch Node** | Routes email to respective category workflow |
| **Google Gemini AI Model** | Generates smart email draft responses |
| **Gmail Draft Node** | Creates AI-generated draft reply in Gmail |

---

## 📸 Workflow Overview  

Below is a visual representation of the Email Classifier workflow in n8n:  

![Email Classifier Workflow](./Email%20Classifer.png)

---

## 🧰 Tools & Technologies  

- **n8n** – Automation and Workflow Orchestration Platform  
- **Gmail API** – Email Trigger and Draft Creation  
- **Google Gemini AI Model** – Natural language understanding and response drafting  
- **AI Agents** – Individual models for each email category  

---

## 💬 Tagline Options  

- **“Smart Email Sorting — Powered by AI and Automation.”**  
- **“Let AI Handle Your Inbox, So You Can Focus on What Matters.”**  
- **“Classify, Respond, and Manage Emails Automatically with n8n.”**  
- **“AI Email Assistant: Organize. Classify. Respond.”**  
- **“Transform Your Inbox into an Intelligent Communication Hub.”**  

---

## 🧑‍💻 Author  

**Hamza Zafar**  
- WordPress & Web Automation Developer  
- Founder at **XpertsWP**  
- 💼 Expertise: WordPress, Elementor, Divi, and Automation Workflows  

---

## 💡 Future Enhancements  

- Integrate **sentiment analysis** for customer emails.  
- Add **auto-send rules** for specific categories (e.g., support confirmations).  
- Include **Slack or WhatsApp notifications** for urgent (Priority) emails.  
- Build a **dashboard** to track categorized email counts and agent performance.  

---

## 🏁 How to Use  

1. Clone or import the workflow JSON file into n8n.  
2. Connect your **Gmail** and **Google Gemini AI** credentials.  
3. Set up Gmail labels: *Priority*, *Support*, *Promotion*, *Finance/Billing*.  
4. Activate the workflow.  
5. Watch your inbox get automatically categorized with AI-generated response drafts.  

---

✅ This README is fully Markdown-compatible and displays perfectly on GitHub with all formatting, tables, and sections intact.
