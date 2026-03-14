# 🤖 LangChain + Ollama + Streamlit AI Assistant

This project is a simple **AI Question-Answering Web App** built using **LangChain**, **Ollama**, and **Streamlit**.
It allows users to enter a question and get an AI-generated response from a locally running **Gemma model** using Ollama.

The application demonstrates how to build a **local LLM-powered application** without relying on external APIs.

---

## 🚀 Features

* 💬 Ask questions through a simple web interface
* 🧠 Uses **local LLM (Gemma:2B)** via Ollama
* 🔗 Built with **LangChain prompt pipelines**
* 🌐 Interactive UI using **Streamlit**
* 🔐 Runs completely **locally (no external API required)**

---

## 🛠️ Tech Stack

* **Python**
* **LangChain**
* **Ollama**
* **Streamlit**
* **Gemma 2B LLM**

---

## 📂 Project Structure

```
AgenticAI/
│
├── app.py               # Main Streamlit application
├── requirements.txt     # Project dependencies
├── .env                 # Environment variables
└── README.md            # Project documentation
```

---

## ⚙️ Installation

### 1️⃣ Clone the repository

```
git clone https://github.com/yourusername/AgenticAI.git
cd AgenticAI
```

---

### 2️⃣ Install dependencies

```
pip install -r requirements.txt
```

---

### 3️⃣ Install Ollama

Download and install Ollama:

https://ollama.com/download

Verify installation:

```
ollama --version
```

---

### 4️⃣ Download the LLM model

```
ollama pull gemma:2b
```

---

## ▶️ Running the Application

Start the Streamlit app:

```
streamlit run app.py
```

Then open your browser and go to:

```
http://localhost:8501
```

You can now ask questions and receive responses from the AI assistant.

---

## 📸 Example

User Input:

```
What is Artificial Intelligence?
```

AI Response:

```
Artificial Intelligence (AI) refers to the simulation of human intelligence in machines...
```

## 👨‍💻 Author---Sachin Kumar Jaiswal
