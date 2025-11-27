# 🔥 Lead Automation System (Google Forms → Zapier → Email → Telegram)

This project demonstrates a **multi-channel lead capture automation workflow** built using:

- Google Forms (Lead input)
- Google Sheets (Lead database)
- Zapier (Automation engine)
- Gmail (Email notifications)
- Telegram Bot (Real-time lead alerts)

This is a real-world automation used by freelancers, startups, and businesses for instant lead processing.

---

## 📌 Features

✔ Users submit a lead through **Google Form**  
✔ Lead is stored automatically in **Google Sheets**  
✔ You receive an **instant email** with the lead details  
✔ You receive a **Telegram alert** using a bot  
✔ Fully automated — no manual work  
✔ Beginner-friendly, business-ready workflow  

---

## 📌 Workflow Overview

<img width="687" height="820" alt="Zapier_setup" src="https://github.com/user-attachments/assets/cfca967e-ecd2-4100-ab2e-7d7af8b68be6" />


User Submits Google Form
↓
Zapier Trigger
↓
Google Sheets (store lead)
↓
Send Email Notification
↓
Send Telegram Notification
## 🚀 Tools Used

- **Google Forms**  
- **Google Sheets**  
- **Zapier (multi-step automation)**  
- **Gmail API**  
- **Telegram Bot API**  
- **Webhooks by Zapier**

---

## ⚙️ How the Automation Works

### 1️⃣ **Trigger: Google Form Submission**
Whenever a user submits the form, Zapier detects a new response.

### 2️⃣ **Action: Add Row to Google Sheets**
The lead is saved in a structured sheet:

| Name | Email | Phone | Message |

### 3️⃣ **Action: Email Notification**
Zapier sends an email with:

- Name  
- Email  
- Phone  
- Message   

### 4️⃣ **Action: Telegram Notification**
Using **Zapier Webhooks (GET)** + Telegram Bot API:

You receive an instant message on Telegram with the lead details.

---

## ⚡ Zapier Steps

See `documentation/zapier-steps.md`

Covers:

- Trigger setup  
- Google Sheets action  
- Email setup  
- Telegram webhook setup  
- Testing workflow  

---

## 🚀 Future Improvements 

Check `documentation/future-improvements.md` for advanced upgrades:

- Connect CRM (Notion / Airtable)
- Add automated follow-up replies
- Lead scoring using AI (ChatGPT)
- Slack/Discord notifications
- Dashboard creation with Power BI

---

## 🧑‍💻 Author

**Pavan Bhavisetti**  
AI Automation Engineer | Zapier | n8n | WhatsApp/Telegram Bots  
LinkedIn: https://www.linkedin.com/in/bhavisetti-pavan-b43a7816a/

---

## ⭐ If you like this project  
Give the repo a **Star ⭐**
