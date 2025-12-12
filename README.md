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
The assistant supports multiple real-world clinical issues:

- **Login Issues**
- **Password Resets**
- **Orders Not Signing**
- **Notes Not Saving**
- **In Basket Messaging Problems**
- **MAR/BCMA Barcode Scanning Issues**
- **Printer / Label Printer Issues**
- **Patient Lookup Failures**
- **General Charting/Documentation Issues**

Each skill is built using:
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
| **ML Pipeline** | Intent classification + entity extraction |
| **CLI Tools** | Model training & testing |

---

## 📁 Project Structure

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
git clone https://github.com/bellronnell-max/Rasa-Epic-support-Assistant.git
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

Demo Scripts

Below are several demo flows that show how the Epic Clinical Support AI Assistant works inside Rasa Shell.

rasa shell

I can't log into Epic
my orders are not signing
epic won't print

hello
I can't log into Epic
I forgot my Epic password
my note won't save
inbasket isn't working
epic won't scan meds
can't find my patient

FULL DEMO (Epic Go-Live Style Conversation)

Paste this entire flow into rasa shell:

hello
my orders are not signing
okay now my note isn’t saving
I'm not receiving In Basket messages
my barcode scanner isn’t scanning meds
I can’t print labels from Epic
I can’t find a newly registered patient
thank you
goodbye

ADVANCED MULTI-INTENT DEMO

hello
I forgot my password
now Epic still won't log me in
okay I got in but now my orders won't sign
and now my note won't save either
can you help with barcode scanners
I also need help printing labels
I'm trying to look up a patient and nothing comes up
thanks for the help
goodbye

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

Author

Ronnell Bell
Epic Support Specialist • AI Engineer • Rasa Developer
📍 El Cajon, California
📞 910-537-9058


This project is licensed under the MIT License.

