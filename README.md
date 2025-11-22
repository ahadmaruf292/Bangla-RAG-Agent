# Bangla-RAG-Agent🤖
![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![Langchain](https://img.shields.io/badge/Built%20with-Lanngchhain-orange)
![Gemini](https://img.shields.io/badge/Model-Gemini%202.5%20pro-purple)
![License](https://img.shields.io/badge/License-Apache2.0-green)

This project is a **Retrieval-Augmented Generation (RAG)** system built using **LangChain** and **Google Gemini**. It allows users to interact with a PDF document by asking natural language questions, receiving accurate answers based on the file's content.

## 🚀 Features

- **Document Processing:** Loads and processes PDF files using `PyPDFLoader`.
- **Vector Embeddings:** Utilizes `models/gemini-embedding-001` for high-quality text embeddings.
- **Efficient Search:** Implements **FAISS** (Facebook AI Similarity Search) for fast information retrieval.
- **Smart Agent:** Powered by the `gemini-2.5-pro` model to generate context-aware responses.
- **Interactive:** Designed to work within a Jupyter Notebook environment.

## 🛠️ Tech Stack

- **Language:** Python 3.10+
- **Framework:** LangChain (Community & Google GenAI)
- **LLM:** Google Gemini (gemini-2.5-pro)
- **Vector Store:** FAISS
- **Environment:** Jupyter Notebook

## 📦 Installation

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/repo-name.git](https://github.com/your-username/repo-name.git)
   cd repo-name
2. Install dependencies:
   pip install -r requirements.txt
3. Set up API Key: Create a .env file in the root directory and add your Google API Key:
  GOOGLE_API_KEY=your_google_api_key_here
