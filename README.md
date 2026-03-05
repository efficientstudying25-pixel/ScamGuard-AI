# 🛡️ ScamGuard AI

[![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python&logoColor=white)](https://www.python.org/) 
[![GitHub Repo](https://img.shields.io/badge/GitHub-Backend-black?logo=github&logoColor=white)](https://github.com/efficientstudying25-pixel/hackathon-backend) 
[![Hackathon MVP](https://img.shields.io/badge/MVP-Hackathon-green)]()
[![Frontend](https://img.shields.io/badge/HTML%2FCSS%2FJS-blueviolet?logo=html5&logoColor=white)](#)


**ScamGuard AI** detects potential scam content in voice input and text messages using a trained ML model.  
It highlights risky keywords, provides risk scores, and explains why a message may be suspicious in hinglish.  

---

## 🗂️ Project Structure

- `app.py` – Backend server exposing `/analyze` API  
- `train_model.py` – Train or retrain the ML model  
- `model/` – Saved ML model files  
- `detection/` – Scam detection logic  
- `utils/` – Helper functions  
- `data/` – Sample datasets or input  
- `frontend/` – HTML, JS, CSS, and logo  
- `Procfile` – Deployment configuration for Render 

---

## ⚡ Features

- ✅ Analyze text messages for scam content  
- ✅ Highlight flagged keywords in messages  
- ✅ Provide risk score & level  
- ✅ Explain reasoning behind prediction in hinglish  

---

## 🎥 Demo

- **Watch the demo:** [Click here](https://drive.google.com/file/d/1Wvtwa83V1Q5bONQExH4UKijmdylNyC9c/view?usp=drivesdk)
- **Try it yourself:** [Live Demo](scam-guard-ai.netlify.app)

⚠️ **Note:**  
The backend is hosted on a **free-tier server**, so the **first request may take a few seconds to load** if the server was inactive.  
After it wakes up, responses are much faster.
- **Frontend + Backend Repo:** [GitHub Link](https://github.com/efficientstudying25-pixel/ScamGuard-AI)

---

## 🛠️ Technologies

- Python 🐍 (ML & backend)  
- HTML / CSS / JavaScript 💻  
- REST API ⚡  

---

## 🚀 Quick Start

1️⃣ **Clone the repository**
```bash
git clone https://github.com/efficientstudying25-pixel/ScamGuard-AI
cd ScamGuard-AI
