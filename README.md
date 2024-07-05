# QA-chatbot
QACbot is an intelligent Question-Answering Chatbot built using the Gemini LLM (Large Language Model) from Google Generative AI. This chatbot leverages advanced natural language processing capabilities to provide accurate and context-aware responses to user queries through an interactive web interface powered by Streamlit.

# Features
Generative AI Integration: Utilizes Google's Gemini Pro model to understand and respond to questions effectively.
User-Friendly Interface: Built with Streamlit, providing a smooth and interactive user experience.
Persistent Chat History: Maintains chat history throughout the session using Streamlit's session state.
Environment Variable Management: Secure handling of sensitive information using python-dotenv

# Code Overview
qachatbot.py: Main application script that sets up the Streamlit interface and handles user interactions.
.env: Environment file to store sensitive information like API keys.

# Key Components in qachatbot.py
1.Environment Setup: Loads environment variables using python-dotenv.
Generative AI Configuration: Configures the google-generativeai library with the Gemini Pro model.
2.Streamlit Interface: Provides a text input for user queries and displays the AI responses.
3.Session State: Uses Streamlit's session state to maintain the chat history.

# Dependencies
The project relies on the following libraries:

1.streamlit: For building the interactive web interface.
2.google-generativeai: For integrating Google's generative AI capabilities.
3.python-dotenv: For managing environment variables.
