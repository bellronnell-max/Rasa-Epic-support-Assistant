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
Supports real-world clinical issues such as:

- **Login Issues**  
- **Password Resets**  
- **Orders Not Signing**  
- **Notes Not Saving**  
- **In Basket Messaging Problems**  
- **MAR/BCMA Barcode Scanning Issues**  
- **Printer / Label Printer Issues**  
- **Patient Lookup Failures**  
- **General Charting / Documentation Issues**

---

## 🧠 Technology Stack

| Component | Description |
|----------|-------------|
| **Rasa Open Source** | NLU & Dialogue engine |
| **Python 3.10** | Runtime environment |
| **YAML** | Model config, intents, rules |
| **ML Pipeline** | Intent classification / entity extraction |
| **CLI Tools** | Training & testing |

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

yaml
Copy code

---

## 🔧 Installation & Setup

### Clone the repository
```bash
git clone https://github.com/bellronnell-max/Rasa-Epic-support-Assistant.git
cd Rasa-Epic-support-Assistant
Create a virtual environment
bash
Copy code
python -m venv venv
venv\Scripts\activate
Install Rasa
bash
Copy code
pip install rasa
Train the model
bash
Copy code
rasa train
Run the assistant
bash
Copy code
rasa shell
💬 Example Queries
"I can’t log into Epic"

"My orders are not signing"

"My note won’t save"

"Inbasket isn’t working"

"Epic won’t scan meds"

"Epic won’t print"

"Can’t find my patient"

🎯 Purpose of This Project
This assistant demonstrates:

Healthcare workflow automation

Rasa NLU/NLP engineering

Real-world medical support AI

Translation of Epic troubleshooting into AI logic

A strong AI engineering portfolio project

👤 Author
Ronnell Bell
Epic Support Specialist • AI Engineer • Rasa Developer
📍 El Cajon, California
📞 910-537-9058

🔮 Future Enhancements
Multi-step troubleshooting flows

Contextual follow-up questions

Web UI

Deployment via Docker or Rasa X

Integration with Helpdesk ticketing APIs
