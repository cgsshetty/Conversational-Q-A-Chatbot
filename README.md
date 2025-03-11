# Conversational Q&A Chatbot - Gemini API

This project enables users to **interact with an AI-powered chatbot** using LangChain and the Gemini API. It provides a Streamlit-based UI for easy and interactive conversations.

## Features
AI-powered conversational Q&A chatbot
 Uses Gemini API for natural language processing
 Streamlit UI for user-friendly interaction

## Requirements
Ensure you have the following installed:
- Python (>=3.8)
- Gemini API Key
- Required Python dependencies

## Installation

### 1️⃣ Clone the Repository**


### 2️⃣ Install Dependencies**

pip install -r requirements.txt


### 3️⃣ Set Up Environment Variables**
Create a `.env` file in the project directory and add your **Gemini API Key**:
```env
GEMINI_API_KEY=your_api_key_here
```

### 4️⃣ **Run the Chatbot**
The `app.py` script contains the chatbot implementation using the Gemini API.

#### Example Usage:
```python
from app import get_response

response = get_response("What is AI?")
print(response)
```
This will return an AI-generated response based on the user's query.

## Running the Streamlit App
To run the **Streamlit UI**, use:
```bash
streamlit run app.py
```

This will open a local UI where users can chat with the AI-powered Q&A chatbot.

## Summary
Conversational chatbot powered by AI
Handles Q&A interactions using Gemini API
User-friendly UI with Streamlit

---

Author: Chirag S Shetty


