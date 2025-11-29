🧠 Python Chatbot (LangChain + LangGraph + OpenRouter)

A simple terminal-based AI chatbot built using LangChain, LangGraph, and OpenRouter. It supports streaming responses and includes a small calculator tool as an example of tool-calling.

🚀 How to Run
1. Clone the project

git clone https://github.com/Mohie-Aldin-Sinan/chatbot

cd chatbot

2. (Optional) Create and activate a virtual environment

python -m venv .venv
.venv\Scripts\activate (Windows)

3. Install dependencies

pip install -r requirements.txt

4. Add your .env file

Create a file named .env in the project root:

OPENAI_API_KEY=your-openrouter-key
OPENAI_API_BASE=https://openrouter.ai/api/v1

5. Run the chatbot

python main.py

🛠️ Features

Chat interface in the terminal

Streaming responses

Tool calling (example: simple calculator)

Supports OpenRouter-compatible models

📦 Tech Stack

Python

LangChain

LangGraph

OpenRouter API

python-dotenv

📌 Notes

This project is intentionally kept minimal and easy to understand, making it a useful base for experimenting with LLMs, adding custom tools, or extending into a full application.
