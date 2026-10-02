\# 🥗 MacroSnap



MacroSnap is an AI-powered nutrition assistant built with Streamlit and Google Gemini.



It allows users to:

\- Enter their name and WhatsApp number

\- Ask nutrition-related questions

\- Upload a photo of a meal

\- Get estimated calories and macronutrients

\- View nutrition information through an interactive chat interface

\- Generate a conversation summary for WhatsApp



\## 🚀 Features



\### 1. Text-based Nutrition Analysis

Users can describe what they ate, and MacroSnap estimates:

\- Calories

\- Protein

\- Carbohydrates

\- Fat



\### 2. Meal Photo Analysis

Users can upload a JPG, JPEG, or PNG image of their meal. Gemini analyzes the image and provides an estimated nutrition breakdown.



\### 3. AI Nutrition Assistant

Google Gemini is used for conversational nutrition analysis and meal understanding.



\### 4. WhatsApp Summary

MacroSnap is designed to generate a summary of the conversation and send it through Twilio WhatsApp.



> Note: WhatsApp message delivery requires the appropriate Twilio WhatsApp Content Template and account permissions.



\## 🛠️ Technologies Used



\- Python

\- Streamlit

\- Google Gemini API

\- Twilio WhatsApp API



\## 📁 Project Structure



```text

macrosnap/

│

├── app.py

├── prompts.py

├── requirements.txt

├── README.md

├── .gitignore

│

└── .streamlit/

&#x20;   └── secrets.toml.example

