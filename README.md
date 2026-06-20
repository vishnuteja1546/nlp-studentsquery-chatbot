# Customer Service NLP Chatbot

An interactive, NLP-powered customer service chatbot built with Python, NLTK, and Gradio. The chatbot uses natural language processing techniques to parse user inputs, identify user intent based on token overlap matching, and deliver relevant automated customer service responses through a sleek web interface.

## 🚀 Features
* **Intent Recognition:** Leverages text preprocessing (tokenization and lowercasing) via NLTK to understand the intent behind user queries.
* **Dynamic Responses:** Maps user messages against a flexible `intents.json` data configuration file.
* **Web UI:** Interactive, modern chat interface powered by Gradio, complete with example query buttons.
* **Colab Ready:** Can be launched and shared directly from a Google Colab notebook with temporary public URL generation.

---

## 🛠️ Tech Stack & Libraries
* **Language:** Python 3
* **NLP Framework:** NLTK (Natural Language Toolkit)
* **User Interface:** Gradio
* **Data Format:** JSON

---

## 📁 Project Structure
* `intents.json` — The configuration file holding intents, training patterns, and response pools.
* `query_chatbot.ipynb` — The primary Google Colab notebook containing text preprocessing, matching logic, and the UI layout.

---

## 💻 Getting Started & Installation

### Run in Google Colab (Recommended)
You can open the notebook directly in Google Colab and run all cells sequentially to spin up the web interface instantly.
