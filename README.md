# AI Research & Web Search Chatbot

An AI-powered chatbot built with Streamlit, LangChain, and Groq LLM that can answer questions by searching multiple knowledge sources in real time.

The chatbot combines:
- 🌐 **DuckDuckGo Search** for live web results
- 📚 **Wikipedia** for factual information
- 📄 **arXiv** for research papers
- 🤖 **Groq Llama 3.1** model for intelligent responses

It provides users with accurate, research-backed answers through a simple chat interface.

## Features

- 💬 Interactive chat interface using Streamlit
- 🔍 Real-time web search
- 📚 Wikipedia integration
- 📄 Research paper search via arXiv
- ⚡ Fast AI responses using Groq Llama 3.1
- 🧠 LangChain Agent automatically selects the best tool
- 🔄 Streaming responses for a better user experience

## Tech Stack

- Python
- Streamlit
- LangChain
- Groq API
- DuckDuckGo Search
- Wikipedia API
- arXiv API
- python-dotenv

## Project Structure
project/
│── app.py
│── requirements.txt
│── .env
└── README.md


## Installation

**Clone the repository**
```bash
git clone https://github.com/yourusername/ai-search-chatbot.git
```

**Move into the project directory**
```bash
cd ai-search-chatbot
```

**Create a virtual environment**
```bash
python -m venv venv
```

**Activate it**

Windows
```bash
venv\Scripts\activate
```

Linux/Mac
```bash
source venv/bin/activate
```

**Install dependencies**
```bash
pip install -r requirements.txt
```

## Run the Application

```bash
streamlit run app.py
```

## Configure API Key

Enter your Groq API Key in the sidebar after launching the application.
You can get a free API key from the [Groq Console](https://console.groq.com).

## How It Works

1. User enters a question.
2. LangChain Agent analyzes the query.
3. The agent decides whether to use:
   - DuckDuckGo
   - Wikipedia
   - arXiv
4. The selected tool retrieves relevant information.
5. Groq's Llama 3.1 model generates a final answer.
6. The response is streamed back to the user.

## Example Questions

- What is Machine Learning?
- Who invented Python?
- Latest AI research on LLMs
- Explain Quantum Computing
- Research papers about Reinforcement Learning
- What happened in today's AI news?

## Future Improvements

- Conversation memory
- Source citations
- PDF document search
- Image generation support
- Voice input/output
- Multiple LLM support (OpenAI, Gemini, Claude)
- Chat history export

## License

This project is open source and available under the MIT License.





