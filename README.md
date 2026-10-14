# 📄 Document Intelligence System — RAG

A Generative AI application that answers natural-language questions about PDF, DOCX, and TXT documents using Retrieval-Augmented Generation (RAG). It retrieves relevant information from uploaded documents and generates context-based answers with source references.

## ✨ Features

* Supports PDF, DOCX, and TXT documents.
* Text chunking and embedding generation.
* Semantic search using FAISS vector storage.
* Context-aware answers using a Large Language Model (LLM).
* Source references to help users verify answers.
* Interactive Streamlit chat interface.

## 🛠️ Tech Stack

Python | LangChain | FAISS | Hugging Face | Sentence Transformers | Groq API | Streamlit | RAGAS

## ⚙️ Workflow

1. Upload PDF, DOCX, or TXT documents.
2. Extract and split text into smaller chunks.
3. Generate embeddings using Sentence Transformers.
4. Store and retrieve relevant chunks using FAISS.
5. Pass the retrieved context to an LLM through Groq.
6. Generate answers grounded in the retrieved documents.
7. Display answers and source references in Streamlit.

## 🧠 Key Concepts

* **RAG:** Combines document retrieval with LLM-based answer generation.
* **Embeddings:** Represent text as numerical vectors for semantic search.
* **FAISS:** Enables efficient similarity search over document embeddings.
* **RAGAS:** Supports evaluation of retrieval and answer quality.

## 🚀 Getting Started

Clone the repository:

```bash
git clone https://github.com/madhu-30505/Document-Intelligence-System.git
cd Document-Intelligence-System
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Configure your Groq API key in a `.env` file:

```env
GROQ_API_KEY=your_groq_api_key
```

Run the application:

```bash
streamlit run app.py
```

*Ensure the commands and environment variables match your actual project configuration.*

## ⚠️ Limitations

* Answer quality depends on document quality and retrieval accuracy.
* Responses may be incomplete if relevant information is not retrieved.
* Evaluation results depend on the quality and size of the evaluation dataset.

## 👩‍💻 Author

**Madhumitha M**
Computer Science and Engineering | Aspiring AI/ML Engineer

[GitHub](https://github.com/madhu-30505) | [LinkedIn](https://linkedin.com/in/madhu0505)
