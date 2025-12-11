# 🏥 Epic Clinical Support AI Assistant (Rasa Framework)

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Rasa](https://img.shields.io/badge/Rasa-Open%20Source-purple)
![Healthcare](https://img.shields.io/badge/Healthcare-Epic-important)
![Project](https://img.shields.io/badge/Project-Conversational%20AI-blueviolet)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)
![License](https://img.shields.io/badge/License-MIT-green)

---

A fully functional **Epic Support AI Assistant** built using the **Rasa** conversational AI framework.  
This assistant replicates the behavior of an Epic Go-Live support agent and provides real-time troubleshooting for common clinician issues inside the Epic EHR.

---

## 🚀 Features

### ✅ Epic Workflow Troubleshooting
The assistant supports multiple real-world clinical issues, including:

- **Login Issues**
- **Password Resets**
- **Orders Not Signing**
- **Notes Not Saving**
- **In Basket Messaging Problems**
- **MAR/BCMA Barcode Scanning Issues**
- **Printer / Label Printer Issues**
- **Patient Lookup Failures**
- **General Charting/Documentation Issues**

Each skill is powered by:
- Custom **intents**
- Domain-specific **NLU training examples**
- Structured **rules**
- Detailed **response handling**

---

## 🧠 Technology Stack

| Component | Description |
|----------|-------------|
| **Rasa Open Source** | NLU + Dialogue Management |
| **Python 3.10** | Runtime environment |
| **YAML** | Intent, rule, and domain configuration |
| **Machine Learning (NLU pipeline)** | Intent classification + entity extraction |
| **CLI Tools** | Model training & testing |

---

## 📁 Project Structure<img width="1536" height="1024" alt="ChatGPT Image Dec 11, 2025, 03_33_47 PM" src="https://github.com/user-attachments/assets/6796461d-1e0c-4ae1-a92f-fd65299d3037" />
<img width="1536" height="1024" alt="ChatGPT Image Dec 11, 2025, 03_33_47 PM" src="https://github.com/user-attachments/assets/5cd9e861-ff6c-4c0b-97b8-dfb9837f2182" />


Rasa-Epic-support-Assistant/
│
├── actions/
├── data/
│ ├── nlu.yml
│ ├── rules.yml
│ └── stories.yml
├── models/
├── domain.yml
├── config.yml
└── credentials.yml


---

## 🔧 Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone <your-repo-url>
cd Rasa-Epic-support-Assistant

python -m venv venv
venv\Scripts\activate

pip install rasa

rasa train

rasa shell

I can't log into Epic
my orders are not signing
my note won't save
inbasket isn't working
epic won't scan meds
epic won't print
can't find my patient

Purpose of This Project

This assistant demonstrates:

Healthcare workflow automation

Rasa NLU/NLP engineering

Domain-specific conversational logic

Translating Epic support knowledge into AI behavior

Real-world Epic troubleshooting embedded into an AI model

Designed for:

AI engineering portfolios

Epic Support Specialist roles

Healthcare IT job applications

Conversational AI developer roles

addAuthor

Ronnell Bell
Epic Support Specialist • AI Engineer • Rasa Developer
📍 El Cajon, California
📞 910-537-9058

Future Enhancements

Add contextual follow-up questions

Multi-turn troubleshooting flows

Web/GUI interface

Deployment using Rasa X or Docker

Integration with hospital helpdesk systems
