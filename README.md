# AI-Chatbot
🤖 AI Chatbot with Memory (OpenRouter + Streamlit)
A context-aware AI chatbot built using Python and Streamlit.
This chatbot uses OpenRouter API to generate intelligent responses
and maintains conversation history for better interaction.


🚀 Features
1. 💬 Real-time chat interface (ChatGPT-like UI)
2. 🧠 Remembers previous conversation (context-aware)
3. 🤖 AI-powered responses using OpenRouter
4. ⚡ Fast and responsive
5. 🔐 Secure API key handling
6. 🖥️ Simple and easy to run


🛠️ Tech Stack
1. Python
2. Streamlit
3. OpenRouter API
4. OpenAI-compatible SDK

⚙️ Setup
1. Install dependencies
pip install streamlit openai

2. Get API Key
Create your API key from:
https://openrouter.ai/keys


▶️ Run the App<br>
streamlit run app.py<br>

Then open:
http://localhost:8501

<br>
💻 Usage
Enter your message in the input box
Chatbot responds instantly
It remembers previous conversation

Example:<br>
You: What is AI? <br>
Bot: Artificial Intelligence (AI) refers to the simulation of human intelligence in machines...

🧠 How It Works
1. Stores chat in session memory
2. Sends conversation history to OpenRouter API
3. Receives AI-generated response
4. Updates memory for continuous conversation

🔒 Security Note
1. Do NOT expose your API key
2. Never hardcode API key in code
3. Keep your key private

📌 Code Example
from openai import OpenAI
import os

client = OpenAI(
    base_url="https://openrouter.ai/api/v1",
    api_key="OPENROUTER_API_KEY"
)


📈 Future Improvements:
1. 🌐 Deploy online
2. 🎨 Improve UI design
3. 💾 Save chat history
4. 🎤 Add voice features


👩‍💻 Author
Tanvi Kambli

⭐ Support
If you like this project:
Star ⭐ the repository
Fork 🍴 it
Contribute 🛠️
