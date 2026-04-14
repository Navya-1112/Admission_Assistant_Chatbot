# Admission_Assistant_Chatbot
A multilingual AI Chatbot for educational institutes built with FastAPI, PyTorch (Neural Networks), and NLTK. Features a custom-trained intent classification model and a responsive, bilingual (English/Hindi) web interface.

# TechSarthi - AI-Powered Institutional Chatbot

TechSarthi is an intelligent, full-stack chatbot solution designed to help students and visitors navigate institutional information such as admissions, courses, fees, and placements. It uses a custom-trained Deep Learning model to understand user queries and provide relevant responses in real-time.

## 🚀 Features
* **Deep Learning Backend:** Built with PyTorch using a Feedforward Neural Network with three linear layers.
* **NLP Processing:** Implements tokenization, stemming (Porter Stemmer), and Bag-of-Words using NLTK.
* **Multilingual Support:** Seamlessly switch between **English** and **Hindi**.
* **FastAPI Integration:** A high-performance Python API for handling chatbot logic and model inference.
* **Interactive UI:** A modern, "Pinterest-style" responsive web interface with a custom-designed avatar.
* **Hybrid Logic:** Combines predefined category buttons with a free-text conversation mode.

## 🛠️ Tech Stack
* **Frontend:** HTML5, CSS3, Vanilla JavaScript
* **Backend:** FastAPI (Python)
* **AI/ML:** PyTorch, NumPy, NLTK
* **Web Server:** Uvicorn

## 📂 Project Structure
* `app.py`: The FastAPI application entry point.
* `model.py`: Neural Network architecture definitions.
* `intents.json`: The training dataset containing tags, patterns, and responses.
* `nltk_utils.py`: Utility functions for text preprocessing.
* `data.pth`: The trained model weights and metadata.
* `index.html` / `index.js`: The frontend interface and client-side logic.

## ⚙️ Installation & Setup

### 1. Clone the repository  
```bash
git clone [https://github.com/your-username/chatbot-main.git](https://github.com/your-username/chatbot-main.git)
cd chatbot-main

2. Set up Python environment

python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install fastapi uvicorn torch nltk numpy

3. Initialize NLTK

import nltk
nltk.download('punkt')

4. Run the Backend

python app.py

5. Launch the Frontend

Simply open index.html in your web browser. Ensure the backend is running to enable the "Free Text" chat feature.

------------------------------------------------------------------------------------------------------------------------
