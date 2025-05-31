# 🧠 SQL-Powered Data Retrieval Assistant

A multilingual, voice-activated assistant that translates natural language queries into executable SQL using OpenAI's EURI LLM. Designed to make database querying accessible for non-technical users.
<br>Designed an AI-powered data cleaning pipeline integrating GPT for intelligent data cleaning, boosting quality by 30%.
<br>Enabled ingestion from diverse sources (CSV, Excel, PostgreSQL) reducing manual ETL time by 40%.



![image](https://github.com/user-attachments/assets/21132ba0-49c3-4e49-8617-f69523c8457e)
![image](https://github.com/user-attachments/assets/e87085dc-b28f-4dec-980f-4fb35e65ae7a)



 <!-- Optional if you have an image -->

---

## 🚀 Features

- 🔎 Natural Language → SQL Conversion using LLM
- 🎙️ Voice Input Support (11+ Languages)
- 🧾 Real-time Schema-Aware Prompt Generation
- 💬 Streamlit-based Interactive UI
- 🛡️ SQL Query Execution with Robust Error Handling
- 🌐 Online PostgreSQL Database Integration

---

## 🗂️ Project Structure

sql-powered-assistant/<br>
<br>├── .env                   # Environment variables (EURI key, DB URI) 
<br>├── app/                   # (Optional) For modular app expansion
<br>├── config.py              # Configuration file for API keys and DB connection
<br>├── main.py                # Streamlit main app (entry point)
<br>├── prompt_template.txt    # Prompt format for the LLM
<br>├── requirements.txt       # Python dependencies
<br>├── utills.py              # Utility functions (LLM call, SQL executor, schema parser)
<br>└── README.md              # Project documentation (this file)




---

## 🛠️ Tech Stack

- **Frontend:** Streamlit
- **Backend:** Python
- **Database:** PostgreSQL (hosted online)
- **LLM API:** EURI (OpenAI-compatible)
- **Voice Recognition:** Google SpeechRecognition API
- **ORM:** NEON a PostgreSQL Online Data Integration

---

## 📦 Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/SVGautham/SQL_POWER_DATA_AGENT
   cd sql-assistant```

2. **python -m venv venv**
```bash
source venv/bin/activate  # or venv\Scripts\activate on Windows
```

3. **Install Dependencies**
```bash
pip install -r requirements.txt
```

4. **Create a .env File**
```bash
EURI_API_KEY=your_euri_api_key
DATABASE_URI=postgresql://username:password@host:port/dbname
```
5. **Running the App**
```bash
streamlit run main.py
```

