# 💬 WhatsApp Automation Script (Python)

This Python script automates sending messages on **WhatsApp Desktop** or **WhatsApp Web** using `pyautogui`, `subprocess`, and `webbrowser`.

## 🚀 Features
- **Open WhatsApp** (Desktop app or Web version)
- **Send a message** to a specific contact number
- **Send multiple messages** in a loop (spam mode — use responsibly!)
- **Close WhatsApp** automatically

## ⚠️ Disclaimer
This script is for **educational purposes only**.  
Do **not** use it for spamming or violating WhatsApp's terms of service.  

---

## 🛠 How It Works
1. **Opens WhatsApp** using:
   - `whatsapp://` protocol for Desktop app
   - Fallback to `https://web.whatsapp.com/` if the app isn't installed
2. **Searches for the contact** using the provided phone number
3. **Writes and sends the message**
4. **Repeats** if `loop` is greater than 0
5. Optionally closes WhatsApp after sending

---

## 📋 Requirements
- Python 3.x  
- Install dependencies:
```bash
pip install pyautogui

📦 WhatsAppAutomation
 ├── whatsapp_bot.py   # Main script
 ├── README.md         # Project documentation

## 🖋 Author
**Abhishek**  
📅 **Created:** 2025
