# GEN_AI_PROJECT
Search engine using tools and agents

🔎 LangChain - Chat with Search

This project is a Streamlit-based chatbot that leverages LangChain and Groq's Chat API to provide intelligent responses using online search tools like DuckDuckGo, Wikipedia, and Arxiv.

🚀 Features

Conversational AI: Chat with an AI assistant powered by LangChain and Groq.

Web Search: Retrieve up-to-date information using DuckDuckGo.

Academic Research: Fetch scholarly articles from Arxiv.

Wikipedia Integration: Extract information from Wikipedia pages.

Interactive UI: User-friendly Streamlit interface with a sidebar for API key input.

🛠️ Installation

1️⃣ Clone the Repository

git clone https://github.com/your-username/langchain-chat-search.git
cd langchain-chat-search

2️⃣ Create a Virtual Environment (Optional but Recommended)

python -m venv myenv
myenv\Scripts\activate    # On Windows

3️⃣ Install Dependencies

pip install -r requirements.txt

4️⃣ Set Up Environment Variables

Create a .env file in the project root and add your Groq API Key:

GROQ_API_KEY=your_api_key_here

▶️ Usage

Run the Streamlit app:

streamlit run app.py

📜 Requirements

Ensure the following dependencies are installed (included in requirements.txt):

streamlit
langchain
langchain-groq
langchain-community
python-dotenv


🖼️ Project Structure

📂 langchain-chat-search
│-- 📄 app.py                # Main Streamlit application
│-- 📄 requirements.txt      # Python dependencies
│-- 📄 .env                  # Environment variables (not included in repo)
│-- 📄 README.md             # Project documentation

🏗️ How It Works:

The user enters a query in the chat input.

The chatbot interacts with LangChain to process the request.

Search tools (DuckDuckGo, Arxiv, Wikipedia) are used to fetch relevant data.

The chatbot provides a response using Groq's LLM.


🤝 Contributing

Pull requests are welcome! Feel free to fork the project and submit improvements.
