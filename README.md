# Chatbot using LangChain & Hugging Face

## About this project

I built this project while learning LangChain and how to work with LLM APIs.
The main idea was to understand how chat-based models work and how we can maintain conversation history.

This is a simple command-line chatbot that uses a Hugging Face model (Llama 3) to generate responses.

---

## What it does

* Takes user input from the terminal
* Keeps track of the conversation
* Sends the full chat history to the model
* Generates a response using Hugging Face

Type `exit` to stop the chatbot.

---

## Tech used

* Python
* LangChain
* Hugging Face Inference API
* python-dotenv

---

## How to run it

### 1. Clone the repo

```id="dphlcz"
git clone https://github.com/your-username/your-repo.git
cd your-repo
```

---

### 2. (Optional) Create a virtual environment

```id="ajvdra"
python -m venv myenv
myenv\Scripts\activate
```

---

### 3. Install dependencies

```id="v81j0r"
pip install langchain langchain-huggingface python-dotenv
```

---

### 4. Create a `.env` file

Add your Hugging Face API key:

```id="sx0fjt"
HUGGINGFACEHUB_API_TOKEN=your_api_key_here
```

> Note: `.env` file is not included in this repo for security reasons.

---

### 5. Run the chatbot

```id="0stfi4"
python chatbot.py
```

---

## What I learned

* How LangChain structures chat using messages
* How to use Hugging Face models via API
* Why we should not expose API keys (using `.env`)
* Basic project setup for GitHub

---

## Notes

* Responses may take a few seconds depending on API speed
* This is a basic version — can be extended with UI, memory storage, etc.

---

## Future improvements (ideas)

* Add a web interface (Streamlit)
* Try different models
* Store chat history
* Improve response quality

---

## Author

Sarib

---
