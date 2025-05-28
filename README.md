# 🧠 SQL-Powered Data Retrieval Assistant

A multilingual, voice-activated assistant that translates natural language queries into executable SQL using OpenAI's EURI LLM. Designed to make database querying accessible for non-technical users.

![Streamlit App Screenshot](screenshot.png) <!-- Optional if you have an image -->

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

sql-powered-assistant/
├── .env                   # Environment variables (EURI key, DB URI) <br>
├── app/                   # (Optional) For modular app expansion
├── config.py              # Configuration file for API keys and DB connection
├── main.py                # Streamlit main app (entry point)
├── prompt_template.txt    # Prompt format for the LLM
├── requirements.txt       # Python dependencies
├── utills.py              # Utility functions (LLM call, SQL executor, schema parser)
└── README.md              # Project documentation (this file)




---

## 🛠️ Tech Stack

- **Frontend:** Streamlit
- **Backend:** Python
- **Database:** PostgreSQL (hosted online)
- **LLM API:** EURI (OpenAI-compatible)
- **Voice Recognition:** Google SpeechRecognition API
- **ORM:** SQLAlchemy

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

