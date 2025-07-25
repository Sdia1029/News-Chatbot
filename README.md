# 📰 News Chatbot

This project is a **Python Flask-based AI chatbot** that delivers up-to-date news summaries and general topic insights through an interactive web interface.  
It combines **live news scraping** with **AI-powered explanations** using **Groq API** for intelligent fallback answers.

---

## 📌 Features

✅ Conversational news assistant  
✅ Automatic news fetching from News API  
✅ AI explanations when no news is found  
✅ Intelligent spelling corrections & topic mapping  
✅ Works via a simple web interface (`index.html`)  
✅ Secure API keys using `.env` file

---

## ⚙️ Technologies Used

- Python 3
- Flask
- NewsAPI.org
- Groq API
- HTML (Jinja templates)
- Requests
- Regex
- Logging

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository

```bash
https://github.com/Sdia1029/News-Chatbot.git
cd news-chatbot
```

---

### 2️⃣ Create & Activate Virtual Environment (Optional but Recommended)

```bash
python -m venv venv
source venv/bin/activate  # On Linux/Mac
venv\Scripts\activate     # On Windows
```

---

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

### 4️⃣ Setup `.env`

Create a `.env` file in the project root and add your API keys:

```
NEWS_API_KEY=your_news_api_key_here
GROQ_API_KEY=your_groq_api_key_here
```

---

### 5️⃣ Run the Application

```bash
python app.py
```

Open your browser and visit [http://127.0.0.1:5000/](http://127.0.0.1:5000/)  
Enter your query and interact with the chatbot!

---

## 📂 Project Structure

```plaintext
news-chatbot/
│
├── app.py
├── templates/
│   └── index.html
├── .env
├── requirements.txt
└── README.md
```

---

## ⚠️ Notes

- Be sure to respect the terms of service for the News API.
- Add reasonable delays or limits if adapting for high-frequency scraping.
- Do not expose your `.env` or API keys in public repositories.

---

## 🙌 Contributing

Pull requests are welcome!  
Open an issue first to discuss improvements or new features.

---

Sadia Eman
Data Science

---

