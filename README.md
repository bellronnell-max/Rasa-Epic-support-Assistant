🏥 Epic Clinical Support AI Assistant (Rasa Framework)












A fully functional Epic Support AI Assistant built using the Rasa conversational AI framework.
This assistant replicates the behavior of an Epic Go-Live support agent and provides real-time troubleshooting for common clinician issues inside the Epic EHR.

🚀 Features
✅ Epic Workflow Troubleshooting

Supports real-world clinical issues such as:

Login Issues

Password Resets

Orders Not Signing

Notes Not Saving

In Basket Messaging Problems

MAR/BCMA Barcode Scanning Issues

Printer / Label Printer Issues

Patient Lookup Failures

General Charting / Documentation Issues

Powered by:

Custom intents

Domain-specific NLU examples

Rule-based & story-based flows

Detailed, realistic support responses

🧠 Technology Stack
Component	Description
Rasa Open Source	NLU & Dialogue engine
Python 3.10	Runtime environment
YAML	Model config, intents, rules
ML Pipeline	Intent classification / entity extraction
CLI Tools	Training & testing
📁 Project Structure
Rasa-Epic-support-Assistant/
│
├── actions/
├── data/
│   ├── nlu.yml
│   ├── rules.yml
│   └── stories.yml
├── models/
├── domain.yml
├── config.yml
└── credentials.yml

🔧 Installation & Setup
1️⃣ Clone the Repository
git clone <your-repo-url>
cd Rasa-Epic-support-Assistant

2️⃣ Create & Activate Virtual Environment
python -m venv venv
venv\Scripts\activate

3️⃣ Install Rasa
pip install rasa

4️⃣ Train the Model
rasa train

5️⃣ Run the Assistant
rasa shell

💬 Example Queries

You can ask the assistant:

"I can't log into Epic"

"My orders are not signing"

"My note won't save"

"Inbasket isn't working"

"Epic won't scan meds"

"Epic won't print"

"Can't find my patient"

🎯 Purpose of This Project

This assistant demonstrates:

Healthcare workflow automation

Rasa NLU/NLP engineering

Domain-specific conversational logic

Translating Epic support knowledge into AI behavior

Real-world troubleshooting embedded into AI models

Useful for:

AI Engineering portfolios

Epic Analyst or Support Specialist roles

Healthcare IT job applications

Conversational AI developer roles

👤 Author

Ronnell Bell
Epic Support Specialist • AI Engineer • Rasa Developer
📍 El Cajon, California
📞 910-537-9058

🔮 Future Enhancements

Multi-step troubleshooting flows

Contextual follow-up questions

Web / GUI interface

Deployment via Rasa X or Docker

Integration with hospital helpdesk APIs
