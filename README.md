Multiple PDF Chatbot
PDF Chatbot is a Streamlit-based application that enables users to interact with a conversational AI model trained on PDF documents. The chatbot extracts information from uploaded PDF files and answers user questions based on the provided context.

Features
PDF Upload: Users can upload multiple PDF files.
Text Extraction: Extracts text from uploaded PDF files.
Conversational AI: Uses the Gemini conversational AI model to answer user questions.
Chat Interface: Provides a chat interface for interacting with the chatbot.

Project Structure
app.py: Main application script.
.env: File containing environment variables.
requirements.txt: Python packages required for the app.
README.md: Project documentation.

Dependencies
PyPDF2
langchain
Streamlit
google.generativeai
dotenv

Acknowledgments
Google Gemini: For providing the underlying language model.
Streamlit: For the user interface framework.
