# AI-Chatbot
🤖 AI Chatbot with Memory (OpenRouter + Streamlit)
A context-aware AI chatbot built using Python and Streamlit.
This chatbot uses OpenRouter API to generate intelligent responses
and maintains conversation history for better interaction.

🚀 Features
💬 Real-time chat interface (ChatGPT-like UI)
🧠 Remembers previous conversation (context-aware)
🤖 AI-powered responses using OpenRouter
⚡ Fast and responsive
🔐 Secure API key handling
🖥️ Simple and easy to run

🛠️ Tech Stack
Python
Streamlit
OpenRouter API
OpenAI-compatible SDK

📂 Project Structure
AI-Chatbot/
│── app.py
│── README.md

⚙️ Setup
1. Install dependencies
pip install streamlit openai

2. Get API Key
Create your API key from:
https://openrouter.ai/keys


▶️ Run the App
streamlit run app.py

Then open:
http://localhost:8501


💻 Usage
Enter your message in the input box
Chatbot responds instantly
It remembers previous conversation

Example:
You: What is AI?
Bot: Artificial Intelligence (AI) refers to the simulation of human intelligence in machines...

🧠 How It Works
Stores chat in session memory
Sends conversation history to OpenRouter API
Receives AI-generated response
Updates memory for continuous conversation

🔒 Security Note
⚠️ Do NOT expose your API key
Never hardcode API key in code
Use environment variables
Keep your key private

📌 Code Example
from openai import OpenAI
import os

client = OpenAI(
    base_url="https://openrouter.ai/api/v1",
    api_key="OPENROUTER_API_KEY"
)


📈 Future Improvements
🌐 Deploy online
🎨 Improve UI design
💾 Save chat history
🎤 Add voice features


👩‍💻 Author
Tanvi Kambli

⭐ Support
If you like this project:
Star ⭐ the repository
Fork 🍴 it
Contribute 🛠️
