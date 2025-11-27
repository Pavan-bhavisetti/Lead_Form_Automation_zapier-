# Setup Instructions

This guide explains how to recreate the automation from scratch.

## 1️⃣ Create Google Form
- Add fields: Name, Email, Phone Number, Message
- Publish form

## 2️⃣ Create Google Sheet
- Add headers:
  - Name
  - Email
  - Phone Number
  - Message
  - Timestamp
- Keep as Sheet1

## 3️⃣ In Zapier: Create a new Zap

### Trigger:
- Google Forms → New Form Response

### Action 1:
- Google Sheets → Create Spreadsheet Row
- Map all fields

### Action 2:
- Gmail → Send Email
- Add lead details in the body

### Action 3:
- Webhooks by Zapier → GET
- URL: `https://api.telegram.org/bot<token>/sendMessage`
- Query params:
  - chat_id = <your_chat_id>
  - text = New Lead Received: {{Name}} - {{Email}}

---

## 4️⃣ Publish Zap
Toggle ON → Zap is live!

## 5️⃣ Test Form
Submit → Check:
- Google Sheet
- Email inbox
- Telegram message
