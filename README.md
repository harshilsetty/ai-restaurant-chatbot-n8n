# 🍔 AI-Powered Restaurant Chatbot (n8n + Gemini + Google Sheets)

This repo contains an **AI-powered restaurant assistant chatbot** built with **n8n**, **Google Gemini API**, and **Google Sheets**.  
It’s a prototype for **HS Restaurant**, designed to show how free & open tools can create real automation solutions.  

---

## ✨ Features
- 🤖 Greets customers in a friendly WhatsApp-style tone  
- 🛒 Takes orders step by step (Name, Item, Quantity)  
- 📦 Checks **Inventory sheet** before confirming orders  
- 📝 Updates **Orders sheet** with customer details, status, and timestamp  
- 🙋 Answers FAQs from the **FAQ sheet**  
- 🧠 Remembers last 10 messages (context memory)  
- 🔡 Ignores small spelling mistakes (e.g., *burgur → burger*)  

---

## 🛠 Tech Stack
- **n8n** (self-hosted via Docker, free & open-source)  
- **Google Gemini API** (free tier used)  
- **Google Sheets** (Inventory, Orders, FAQ database)  

---

## 🚀 How to Use
1. Clone this repo or download the JSON file:  
   - [`AI-powered-restaurant-chatbot-sanitized.json`](./AI-powered-restaurant-chatbot-sanitized.json)  

2. Import into your **n8n instance**.  

3. Configure credentials:  
   - Add your **Google Sheets account** in n8n  
   - Add your **Gemini API key** in n8n  

4. Replace placeholders in the workflow:  
   - `REPLACE_WITH_YOUR_SHEET_ID` → your Google Sheet ID  
   - `REPLACE_WITH_YOUR_SHEET_GID` → your sheet tab GID  

5. Run the workflow → start chatting 🎉  

---

## 📂 Google Sheets Structure
Create a Google Sheet (Hotel Management System - HMS) with **3 tabs**:  
1. **Inventory** → Food item, Available quantity  
2. **Orders** → Customer Name, Item, Quantity, Date, Status  
3. **FAQ** → Question, Answer  

---

## 🎥 Demo
👉 [Add your demo video link here once uploaded]  

---

## ⚡ Why This Project?
This is an experiment to show how **AI + automation + no-code workflows** can be combined to build practical business tools with **free resources**.  

Future possibilities:  
- Payment integration  
- Delivery tracking  
- Multi-restaurant support  

---

## 📜 License
MIT – free to use & modify.  
