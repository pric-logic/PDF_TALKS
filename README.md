# PDF_TALKS--📄 Multimodal RAG Pipeline using LangChain, Unstructured & GPT-4o

A Retrieval-Augmented Generation (RAG) pipeline that can intelligently parse and query complex PDFs with **text**, **tables**, and **images** using a multimodal approach. Built with [LangChain](https://github.com/langchain-ai/langchain), [Unstructured](https://github.com/Unstructured-IO/unstructured), and OpenAI's GPT-4o.

---

## 🚀 Features

- ✅ Extracts text, tables, and images from PDFs
- 🧠 Summarizes each element for semantic search
- 📦 Stores data in a vector database (FAISS, Chroma, or Weaviate)
- 🔍 Retrieves information using LangChain's RAG pipeline
- 📎 Links summaries to original document segments

---

## 🧰 Tech Stack

| Component        | Tool/Library        |
|------------------|---------------------|
| Document Parsing | [Unstructured](https://github.com/Unstructured-IO/unstructured) |
| Text Summarization | Open-source models on Groq |
| Image Summarization | GPT-4o-mini (OpenAI) |
| RAG Framework    | [LangChain](https://github.com/langchain-ai/langchain) |
| Vector Store     | FAISS / Chroma / Weaviate |
| Orchestration    | Python / Jupyter Notebook |

---


