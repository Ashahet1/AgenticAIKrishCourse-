# Basic Chatbot Project

This repository contains an end-to-end implementation of a basic chatbot. The chatbot is built using Python and leverages **Streamlit** for the UI, **vector databases** for memory, and a **graph-based approach** for processing queries.

## 📁 Project Structure

```
├── LLMS/               # Contains Language Model components
├── __pycache__/        # Python cache files
├── graph/              # Graph-based query processing
├── nodes/              # Nodes for handling modular logic
├── state/              # Managing chatbot state
├── tools/              # Utility scripts and additional tools
├── ui/                 # Streamlit UI implementation
├── vectorstore/        # Vector database for storing embeddings
├── __init__.py         # Python package initialization
├── main.py             # Entry point for chatbot application
```

## 🚀 Features

- **Interactive UI**: Built using **Streamlit** for ease of interaction.
- **Graph-Based Processing**: Uses nodes and state management to process queries effectively.
- **Vector Search**: Leverages a vector database to store and retrieve contextual embeddings.
- **Modular Structure**: Easily extendable with tools, nodes, and LLM modules.

## 📦 Installation

Ensure you have **Python 3.8+** installed. Clone this repository and install dependencies:

```bash
git clone <repository-url>
cd <project-directory>
pip install -r requirements.txt
```

## ▶️ Running the Chatbot

To start the chatbot, run:

```bash
streamlit run main.py
```

## ⚙️ Configuration

Modify **LLMS/** and **vectorstore/** as needed to integrate with different **LLMs** or storage solutions.

## 📌 Notes

- If there are **Streamlit UI errors**, check dependencies and ensure the necessary packages are installed.
- The project is structured to allow easy modifications for different chatbot applications.

## 📜 License

This project is open-source and available under the **MIT License**.

## Result


