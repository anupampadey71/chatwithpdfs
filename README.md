# Q&A Chatbot from PDFs

This project is a Q&A chatbot that processes PDFs to answer questions using Google Gemini, FAISS as the vector database, and Streamlit for the frontend.

## Features

- Upload PDF files and process them to extract text.
- Use Google Gemini for generating responses based on PDF content.
- Store and search document embeddings using FAISS.
- Interactive frontend with Streamlit.

## Setup

1. **Create and Activate the Conda Environment**

   ```bash
   conda create -n venv_gemini python==3.10 -y
   conda activate venv_gemini
   ```
2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Streamlit Application**
   ```bash
   streamlit run chatpdf1.py
   ```

5. **Configuration**
   Create a .env file in your project directory with your Google API key:
   GOOGLE_API_KEY="your_google_api_key_here"

   
