===========================================================
🏥 AI GENERAL HEALTH QUERY CHATBOT
===========================================================

DESCRIPTION:
This is a Python-based conversational agent designed to provide
general health information. It uses the Hugging Face Inference 
API to connect to a Large Language Model (Llama-3-8B).

FEATURES:
- Natural Language Understanding: Ask health questions in plain English.
- Safety Guardrails: Hard-coded emergency detection and AI disclaimers.
- Beautiful UI: Color-coded terminal output for better readability.

PREREQUISITES:
1. Python 3.8 or higher installed.
2. A Hugging Face Access Token (Read permissions).
3. Internet connection to reach the Hugging Face API.

INSTALLATION:
Install the required library using pip:
   pip install huggingface_hub

SETUP:
1. Open the script/notebook.
2. Replace 'YOUR_HF_TOKEN' with your actual Hugging Face token.
3. Ensure the MODEL_ID is set to "meta-llama/Meta-Llama-3-8B-Instruct".

HOW TO RUN:
- If using a .py file: Run 'python health_chatbot.py' in your terminal.
- If using a .ipynb file: Run all cells in order.

EXAMPLE QUERIES:
- "What causes a sore throat?"
- "How many hours of sleep does an adult need?"
- "Is paracetamol safe for children?"

⚠️ MEDICAL DISCLAIMER:
This bot is an AI assistant, not a doctor. It does not provide 
medical diagnoses or professional medical advice. In case of 
an emergency, always contact local emergency services immediately.

===========================================================
Created as part of Task 4: General Health Query Chatbot
===========================================================