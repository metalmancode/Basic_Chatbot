# Basic AI Chatbot (Part 1 - Seq2Seq)

A simple, terminal-based chatbot built with Python and Hugging Face's `transformers` library. This project serves as an introduction to how transformer models generate dialogue using a sequence-to-sequence approach.

## 🚀 Features
- **Lightweight Model**: Uses `facebook/blenderbot-400M-distill`.
- **Manual History Tracking**: Demonstrates how to store and pass conversation context manually.
- **CPU Optimized**: Runs smoothly on any modern CPU.

## ⚙️ Setup
1. **Clone**: `git clone https://github.com/metalmancode/basic_chatbot.git`
2. **Environment**: 
   ```bash
   python3 -m venv my_env
   source my_env/bin/activate
   pip install transformers torch numpy
   ```
3. **Run**: `python chatbot.py`

## 🧠 What You'll Learn
- How tokenization works.
- How to load pre-trained models from Hugging Face.
- How to maintain a manual conversation history list.

---
*For the advanced version with a Web UI and Modern LLM, see [Basic_Chatbot_Upgraded](https://github.com/metalmancode/Basic_Chatbot_Upgraded).*
