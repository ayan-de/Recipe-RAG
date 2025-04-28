# 🍳 Recipe Search RAG App

Welcome to **Recipe Search RAG App** — a smart AI application that helps you find recipes from a recipe book using **OpenAI embeddings** and **Retrieval-Augmented Generation (RAG)** techniques!

Upload a recipe book, ask anything about it, and get accurate answers instantly!

---

## 🚀 Features

- 📖 Upload a full **PDF recipe book**.
- 🖼️ **Convert PDF pages into images** for better parsing.
- 🧠 **Embed text** from the book using **OpenAI text embeddings**.
- 🔍 **Semantic search**: Find recipes or ingredients with natural language queries.
- 🤖 **Answer generation**: AI retrieves and responds based on your uploaded book.

---

## 📚 How It Works

1. **PDF Upload**: Upload your recipe book.
2. **Preprocessing**:
   - PDF is split into images.
   - Text is extracted and cleaned.
3. **Embedding**:
   - Text chunks are embedded using OpenAI's embedding API.
   - Embeddings are stored for fast retrieval.
4. **User Query**:
   - Your query is embedded and matched to the most relevant recipe text.
   - Retrieved context is passed to OpenAI for generating an answer.

---

## 🛠️ Tech Stack

- **Python**
- **OpenAI API** (Embeddings + GPT for responses)
- **PyMuPDF** (for PDF parsing)
- **FAISS / Similarity Search**

---

## ✨ Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
