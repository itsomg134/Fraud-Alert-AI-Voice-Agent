# Fraud-Alert-AI-Voice-Agent

<div align="center">

![Version](https://img.shields.io/badge/Version-1.0.0-blue)
![AI](https://img.shields.io/badge/AI-Fraud%20Detection-orange)
![Python](https://img.shields.io/badge/Python-3.11-yellow?logo=python)
![Voice Agents](https://img.shields.io/badge/Voice%20Agents-MVP-green)
![Murf Falcon](https://img.shields.io/badge/TTS-Murf%20Falcon-purple)
![License](https://img.shields.io/badge/License-MIT-green)

**Your Complete Fraud Alert AI Voice Agent**
Demo-ready, handles mock bank fraud verification using AI-powered TTS voice interactions.

[Features](#-features) • [Demo](#-demo-video) • [Quick Start](#-quick-start) • [Author](#-author)

</div>

---

# 🚀 Built a Bank Fraud Alert AI

*A sandbox AI voice agent that simulates fraud alert calls for a bank. Designed for demo and learning purposes using fake data only.*

---

## 📌 Overview

This repository provides a **step-by-step implementation** of a fraud alert voice agent:

* 🤖 **AI-powered fraud voice agent**
* 🧾 **Fake database of transactions**
* 🎤 **Text-to-speech (TTS) using Murf Falcon**
* ✅ **Verification flow** (non-sensitive info)
* 📊 **Transaction status logging**
* ☎️ **Optional LiveKit Telephony integration**

Perfect for developers, AI enthusiasts, and anyone learning voice agent integration with banking-like workflows.

---

## 🎯 Features

### ✔ **Fraud Case Database**

* JSON-based mock transactions
* Includes fake user name, card, amount, merchant, timestamp
* Simple security questions for verification

### ✔ **Voice Agent Flow**

* Greets user as bank fraud representative
* Performs safe identity verification
* Reads suspicious transaction details
* Confirms legitimacy (yes/no)
* Updates transaction status in database:

  * `confirmed_safe`
  * `confirmed_fraud`
  * `verification_failed`

### ✔ **MVP TTS Integration**

* Uses Murf Falcon API for natural AI voice
* Runs in browser without telephony
* Easy to extend for multiple cases

### ✔ **Optional Advanced Telephony**

* Integrate with **LiveKit Telephony**
* Handle real phone calls for fraud verification
* Persist outcomes back to database

---

## 🎬 Demo Video

Watch the fraud alert agent in action:

🔗 [Demo Video](https://drive.google.com/file/d/1txCNPWyWqrocn4XY-J23j6d_56pdOzv1/view?usp=vids_web)

---

## ⚡ Quick Start

Clone the repository:

```bash
git clone https://github.com/your-username/bank-fraud-alert-ai.git
cd bank-fraud-alert-ai
```

Install dependencies (Python example):

```bash
pip install -r requirements.txt
```

Run the voice agent (MVP):

```bash
python main.py
```

> Follow the terminal prompts for username and verification flow.

---

## 📁 Project Structure

```
/Bank-Fraud-Alert-AI
│
├── backend/
│   ├── fraud_cases.json
│   ├── main.py
│   └── utils.py
├── frontend/
│   ├── index.html
│   └── voice_agent.js
├── demo_videos/
├── README.md
└── requirements.txt
```

---

## 🚀 Future Improvements

* Multiple fraud cases & advanced workflow
* DTMF input support for telephony
* AI-driven fraud scoring and alerts
* Real-time dashboard for case tracking
* Integration with SMS/email notifications

---

## 👨‍💻 Author

**Om Gedam**
GitHub: [@itsomg134](https://github.com/itsomg134)
Email: [omgedam123098@gmail.com](mailto:omgedam123098@gmail.com)
Twitter (X): [@omgedam](https://twitter.com/omgedam)
LinkedIn: [Om Gedam](https://www.linkedin.com/in/omgedam)
Portfolio: [ogworks.lovable.app](https://ogworks.lovable.app)

Made with ❤️ for learners building AI-powered voice applications and fraud detection demos.

Do you want me to do that?
