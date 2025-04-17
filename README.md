# 🧠 AI Chatbot using LangChain & Ollama

This is a simple terminal-based AI chatbot built using Python, [LangChain](https://www.langchain.com/), and [Ollama](https://ollama.com/). It uses a local LLM (like LLaMA3) to generate responses based on user input and previous conversation history.

---

## 🚀 Features

- Chat with an LLM locally (no internet API required)
- Maintains basic conversation context
- Easy to understand and beginner-friendly code

---

## 🛠️ Tech Stack

- Python 3
- LangChain
- Ollama (LLaMA3)
- Terminal / Command Line Interface

---

## 📦 Installation

1. Clone this repo:

```bash
git clone https://github.com/Akilasudhakar/aichatbot.git
cd aichatbot

Set up virtual environment:

bash
Copy
Edit
python -m venv venv
venv\Scripts\activate   # On Windows

Install dependencies:

bash
Copy
Edit
pip install langchain langchain_ollama
Start Ollama with LLaMA3 model:

bash
Copy
Edit
ollama run llama3
Run the chatbot:

bash
Copy
Edit
python main.py
💬 Example
text
Copy
Edit
Welcome to the AI ChatBot! Type 'exit' to quit.
You: Hello!
Bot: Hey there! How can I help you?

You: Tell me a joke
Bot: Why don't scientists trust atoms? Because they make up everything!
📁 File Structure
bash
Copy
Edit
aichatbot/
├── main.py           # Main chatbot script
├── README.md         # This file
└── venv/             # Python virtual environment (optional, can be .gitignored)

📌 Notes
Make sure you have Ollama installed and set up locally.

Tested with LLaMA3 model locally via Ollama.



