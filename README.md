# 🤖 TaskBot – AI Powered Task Manager

TaskBot is an AI-powered task management assistant that allows users to create, read, update, and delete tasks using natural language. It integrates **LangChain**, **Groq LLM**, **SQLite database**, and **Streamlit UI**.

---

## 🚀 Features

* 📋 Create, update, delete, and view tasks
* 🗄️ SQLite database integration
* ⚡ Powered by Groq LLM (fast inference)
* 💬 Chat-based UI using Streamlit
* 🔄 Maintains session-based conversation history

---

## 🛠️ Tech Stack

* **Python**
* **LangChain**
* **LangGraph**
* **Groq LLM**
* **SQLite**
* **Streamlit**

---

## 📂 Project Structure

```
techsim/
│── apps/
│   └── 1_qna_bot.py
│── Notebooks/
│── venv/
│── requirements.txt
│── .env
│── sql_agent.py
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/taskbot.git
cd taskbot
```

### 2. Create virtual environment

```bash
python -m venv venv
```

### 3. Activate environment

**Windows:**

```bash
venv\Scripts\activate
```

**Mac/Linux:**

```bash
source venv/bin/activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

---

## 🔑 Environment Variables

Create a `.env` file in the root directory:

```
GROQ_API_KEY=your_api_key_here
```

---

## ▶️ Run the App

```bash
streamlit run sql_agent.py
```

---

## 💡 Example Commands

You can interact with the bot like:

* "Add a task to complete my assignment"
* "Show my pending tasks"
* "Mark task 1 as completed"
* "Delete task 2"

---

## 🧠 How It Works

* Uses **LangChain Agent** to interpret user input
* Converts natural language → SQL queries
* Executes queries on SQLite database
* Returns structured responses in chat UI

---

## 📊 Database Schema

| Column      | Type      | Description                       |
| ----------- | --------- | --------------------------------- |
| id          | INTEGER   | Primary Key                       |
| title       | TEXT      | Task title                        |
| description | TEXT      | Task details                      |
| status      | TEXT      | pending / in_progress / completed |
| created_at  | TIMESTAMP | Auto timestamp                    |

---

## 🔥 Future Improvements

* ✅ User authentication
* 📱 Mobile-friendly UI
* ☁️ Cloud database integration
* 📊 Task analytics dashboard

---

## 🤝 Contributing

Feel free to fork this repo and submit pull requests!

---

## 📜 License

This project is open-source

---


⭐ If you like this project, don’t forget to star the repo!
