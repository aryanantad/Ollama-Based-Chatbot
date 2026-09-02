# 🤖 Ollama-Based Chatbot

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.11+-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Ollama-Local%20LLM-black?style=for-the-badge" alt="Ollama">
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" alt="Streamlit">
  <img src="https://img.shields.io/badge/AI-Generative%20AI-8A2BE2?style=for-the-badge" alt="Generative AI">
</p>

<p align="center">
  <b>A beginner-friendly Generative AI chatbot built with Python, Ollama, and Streamlit.</b>
</p>

<p align="center">
  Run Large Language Models locally and interact with them through a simple conversational interface.
</p>

---

## 📌 Overview

**Ollama-Based Chatbot** is a Python-based Generative AI project that demonstrates how to interact with locally hosted Large Language Models using **Ollama**.

The project starts with basic communication between Python and Ollama and gradually builds toward an interactive **Streamlit chatbot application**.

It is designed to help understand the fundamentals of:

* 🧠 Local Large Language Models (LLMs)
* 🔗 Python–Ollama integration
* 💬 Conversational AI
* 🖥️ Streamlit applications
* ⚡ Local AI inference
* 🔄 Sending prompts and receiving model responses

The project is especially useful for developers who want to experiment with **Generative AI without relying entirely on cloud-based APIs**.

---

## ✨ Features

* 🤖 Interact with locally running LLMs
* 🧠 Use Ollama to run AI models locally
* 🐍 Simple Python integration
* 💬 Interactive chatbot functionality
* 🌐 Streamlit-based web interface
* 🔄 Conversation-style interaction
* ⚡ Local inference
* 🔐 No API key required for Ollama's local models
* 📚 Step-by-step examples for learning

---

## 🏗️ Project Structure

```text
Ollama-Based-Chatbot/
│
├── 1_python_ollama.py
├── 2_streamlit_example.py
├── 3_chatbot_echo.py
├── 4_chatbot_ollama.py
│
├── requirements.txt
├── .gitignore
└── README.md
```

### 📂 File Description

| File                     | Description                                                 |
| ------------------------ | ----------------------------------------------------------- |
| `1_python_ollama.py`     | Demonstrates basic communication between Python and Ollama  |
| `2_streamlit_example.py` | Introduction to building a Streamlit interface              |
| `3_chatbot_echo.py`      | Demonstrates basic chatbot interaction and message handling |
| `4_chatbot_ollama.py`    | Complete Ollama-powered chatbot using Streamlit             |
| `requirements.txt`       | Contains the required Python dependencies                   |

---

## 🔄 How It Works

The application follows a simple workflow:

```text
             User
               │
               ▼
       ┌─────────────────┐
       │ Streamlit UI    │
       └────────┬────────┘
                │
                ▼
       ┌─────────────────┐
       │ User Prompt     │
       └────────┬────────┘
                │
                ▼
       ┌─────────────────┐
       │ Python Backend  │
       └────────┬────────┘
                │
                ▼
       ┌─────────────────┐
       │     Ollama      │
       │   Local LLM     │
       └────────┬────────┘
                │
                ▼
       ┌─────────────────┐
       │ AI Response     │
       └────────┬────────┘
                │
                ▼
             User
```

The user enters a prompt through the Streamlit interface. Python sends the prompt to the locally running Ollama model, receives the generated response, and displays it in the chatbot interface.

---

## 🛠️ Tech Stack

### Programming Language

* **Python**

### Generative AI

* **Ollama**
* **Large Language Models (LLMs)**
* **Local AI Inference**

### Frontend / Interface

* **Streamlit**

### Development Tools

* Git
* GitHub
* VS Code
* Python Virtual Environment

---

## ⚙️ Prerequisites

Before running the project, make sure you have:

* **Python 3.11 or higher**
* **Ollama**
* Git
* VS Code or another Python-compatible IDE

Install Ollama from:

https://ollama.com/

After installing Ollama, download a model.

For example:

```bash
ollama pull llama3.2
```

You can replace `llama3.2` with another model supported by Ollama.

---

## 🚀 Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/aryanantad/Ollama-Based-Chatbot.git
```

Navigate into the project:

```bash
cd Ollama-Based-Chatbot
```

---

### 2️⃣ Create a Virtual Environment

```bash
python -m venv venv
```

### Windows

```bash
venv\Scripts\activate
```

### macOS / Linux

```bash
source venv/bin/activate
```

---

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the Project

### Basic Python Example

```bash
python 1_python_ollama.py
```

### Streamlit Example

```bash
streamlit run 2_streamlit_example.py
```

### Echo Chatbot

```bash
streamlit run 3_chatbot_echo.py
```

### 🚀 Full Ollama Chatbot

```bash
streamlit run 4_chatbot_ollama.py
```

After running the Streamlit application, open the URL displayed in your terminal, usually:

```text
http://localhost:8501
```

---

## 🧪 Example Interaction

```text
User:
Explain Machine Learning in simple words.

AI:
Machine Learning is a branch of Artificial Intelligence
that allows computers to learn patterns from data and
make predictions or decisions without being explicitly
programmed for every task.
```

---

## 🎯 Learning Objectives

This project helped explore several important Generative AI concepts:

### 1. Local LLMs

Understanding how Large Language Models can be executed locally using Ollama.

### 2. Prompt → Response Pipeline

Understanding how user prompts are sent to an LLM and how generated responses are returned.

### 3. Python + LLM Integration

Learning how Python applications can communicate with locally hosted AI models.

### 4. Streamlit

Building a lightweight web interface for an AI application using Python.

### 5. Generative AI Fundamentals

Understanding the basic architecture behind an LLM-powered chatbot.

---

## 🔮 Future Improvements

Some planned improvements for the project include:

* [ ] 💾 Persistent chat history
* [ ] 🧠 Conversation memory
* [ ] 🎨 Improved chatbot UI
* [ ] 📄 PDF/document upload
* [ ] 🔍 RAG-based question answering
* [ ] 🗃️ Vector database integration
* [ ] 🎙️ Voice input and output
* [ ] 🌐 Multi-model selection
* [ ] ⚙️ Model parameter controls
* [ ] 📊 Response and token analytics

---

## 📸 Application Preview

> Add screenshots of the Streamlit chatbot here to make the repository more visually attractive.

```text
📷 Screenshot 1 — Chatbot Interface

📷 Screenshot 2 — User Prompt & AI Response

📷 Screenshot 3 — Ollama Model Running Locally
```

---

## 💡 Why Ollama?

Ollama makes it easier to run and experiment with Large Language Models locally.

This project uses Ollama to demonstrate how developers can build AI applications around local models while keeping the development workflow simple.

---

## 🤝 Contributing

Contributions are welcome!

If you have an idea for improving the chatbot:

1. Fork the repository
2. Create a new branch

```bash
git checkout -b feature/new-feature
```

3. Make your changes
4. Commit your changes

```bash
git commit -m "Add new feature"
```

5. Push the branch

```bash
git push origin feature/new-feature
```

6. Open a Pull Request

---

## 📜 License

This project is open-source and available for learning and experimentation.

---

## 👨‍💻 Author

### Aryan Antad

AI & Machine Learning Engineer | Generative AI | Python | Data Science

<p>
  <a href="https://github.com/aryanantad">
    <img src="https://img.shields.io/badge/GitHub-Aryan%20Antad-181717?style=for-the-badge&logo=github" alt="GitHub">
  </a>
</p>

---

<p align="center">
  ⭐ If you found this project useful, consider giving it a star!
</p>

<p align="center">
  <b>Built with 🐍 Python + 🤖 Ollama + ⚡ Streamlit</b>
</p>
