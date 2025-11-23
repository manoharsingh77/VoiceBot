# Intelligent Voice Bot for Customer Interaction


---

## 📖 Project Overview
This project implements an **Intelligent Voice Bot** capable of handling customer banking queries. It leverages **Google Dialogflow CX** for Natural Language Understanding (NLU) and speech processing, integrated with a **Python Flask** backend to handle business logic, database simulation, and real-time analytics.

### 🎯 Key Features Implemented
1.  **Speech-to-Text & Text-to-Speech:** Utilized Dialogflow CX's native voice capabilities.
2.  **Natural Language Understanding (NLU):** Custom Intent recognition (`check_balance`) and Entity extraction (`account_number`).
3.  **Backend Integration:** A Python Flask Webhook that queries a simulated database.
4.  **Dynamic Response Generation:** Responses are generated based on real-time data lookup.
5.  **Analytics Dashboard:** A live web dashboard tracking call logs, user queries, and system status.

---

## 🛠️ Tech Stack
* **Frontend / AI Engine:** Google Dialogflow CX
* **Backend:** Python 3.10 + Flask
* **Tunneling:** Ngrok (to expose local/Colab server to the cloud)
* **Database:** JSON-based mock database (`mock_db.json`)
* **Visualization:** HTML/CSS (for the Analytics Dashboard)

---

## 📂 Project Structure
```text
VoiceBot_Assignment/
│
├── app.py                 # Main application logic (Webhook + Dashboard)
├── mock_db.json           # Simulated database containing user accounts
├── requirements.txt       # Python dependencies
├── README.md              # Project documentation
│
└── templates/             # Frontend templates for the dashboard
    └── dashboard.html     # The analytics dashboard UI
