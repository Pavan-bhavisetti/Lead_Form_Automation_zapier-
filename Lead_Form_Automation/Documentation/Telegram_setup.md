# Telegram Bot Setup Guide

## 1️⃣ Create Bot with BotFather
- Search: BotFather
- /newbot
- Give name & username
- Receive bot token

## 2️⃣ Start Your Bot
- Search your bot username in Telegram
- Press START

## 3️⃣ Get Chat ID
- Search: @userinfobot
- Copy "Your User ID"

## 4️⃣ Test Bot API
Paste in browser:
https://api.telegram.org/bot<token>/sendMessage?chat_id=<chat_id>&text=Hello

You should receive a Telegram message.

## 5️⃣ Connect to Zapier Webhook
App: Webhooks by Zapier → GET

URL:
https://api.telegram.org/bot<token>/sendMessage

Params:
- chat_id
- text

Test → Success!
