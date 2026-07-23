# 📚 Book Search AI using Retrieval-Augmented Generation (RAG)

![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)
![LangChain](https://img.shields.io/badge/LangChain-RAG-green)
![ChromaDB](https://img.shields.io/badge/Vector%20DB-ChromaDB-orange)
![Transformers](https://img.shields.io/badge/HuggingFace-Transformers-yellow)
![SentenceTransformers](https://img.shields.io/badge/SentenceTransformers-Embeddings-red)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

---

## 📖 Overview

Book Search AI is a Retrieval-Augmented Generation (RAG) system that recommends books based on natural language queries. The project combines semantic search, vector embeddings, cross-encoder re-ranking, and Large Language Models (LLMs) to provide accurate and context-aware book recommendations.

Developed as part of the **Advanced Certificate Program in Generative AI (upGrad, August 2023)**, this project demonstrates the complete RAG pipeline, including the embedding layer, search layer, re-ranking layer, and generation layer.

---

# 🚀 Features

- Semantic book search using vector embeddings
- Vector database with ChromaDB
- Similarity search using Sentence Transformers
- Cross-Encoder re-ranking
- Retrieval-Augmented Generation (RAG)
- Prompt engineering for recommendation generation
- Search result caching
- End-to-end recommendation pipeline

---

# 🏗️ Project Architecture

```
                   User Query
                        │
                        ▼
             Query Embedding Model
                        │
                        ▼
              ChromaDB Vector Search
                        │
                        ▼
            Top-k Retrieved Documents
                        │
                        ▼
          Cross Encoder Re-ranking
                        │
                        ▼
          Context Construction (RAG)
                        │
                        ▼
             Large Language Model
                        │
                        ▼
            Final Book Recommendation
```

---

# ⚙️ Tech Stack

| Category | Technology |
|-----------|------------|
| Programming | Python |
| Notebook | Jupyter |
| Embeddings | Sentence Transformers |
| Vector Database | ChromaDB |
| Retrieval | Semantic Search |
| Re-ranking | Cross Encoder |
| LLM | OpenAI GPT |
| Framework | LangChain |
| ML | Hugging Face Transformers |

---

# 📂 Repository Structure

```
book-search-ai-rag/
│
├── Book_Search_AI.ipynb
├── README.md
├── requirements.txt
├── LICENSE
├── .gitignore
│
├── screenshots/
│   ├── search_layer/
│   ├── reranking_layer/
│   └── generation_layer/
│
├── docs/
│
└── data/
```

---

# 🔄 Workflow

1. Load the book dataset.
2. Clean and preprocess book metadata.
3. Generate embeddings using Sentence Transformers.
4. Store embeddings in ChromaDB.
5. Convert the user query into an embedding.
6. Retrieve the most similar books.
7. Re-rank retrieved results using a Cross Encoder.
8. Pass the top-ranked results to the LLM.
9. Generate the final recommendation.

---

# 📊 Search Layer Results

The search layer retrieves the most semantically relevant books using vector similarity search.

| Query | Screenshot |
|--------|------------|
| Query 1 | `screenshots/search_layer/Search_Layer1.png` |
| Query 2 | `screenshots/search_layer/Search_Layer2.png` |
| Query 3 | `screenshots/search_layer/Search_Layer3.png` |

---

# 🔄 Re-ranking Results

A Cross Encoder improves the ordering of retrieved books before they are passed to the LLM.

| Query | Screenshot |
|--------|------------|
| Query 1 | `screenshots/reranking_layer/ReRank_Layer_1.png` |
| Query 2 | `screenshots/reranking_layer/ReRank_Layer_2.png` |
| Query 3 | `screenshots/reranking_layer/ReRank_Layer_3.png` |

---

# 🤖 Generated Recommendations

The LLM uses the re-ranked search results to produce the final recommendation.

| Query | Screenshot |
|--------|------------|
| Query 1 | `screenshots/generation_layer/Generative_Layer_1.png` |
| Query 2 | `screenshots/generation_layer/Generative_Layer_2.png` |
| Query 3 | `screenshots/generation_layer/Generative_Layer_3.png` |

---

# ▶️ Installation

Clone the repository

```bash
git clone https://github.com/yourusername/book-search-ai-rag.git
```

Navigate to the project

```bash
cd book-search-ai-rag
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

Open

```
Book_Search_AI.ipynb
```

Run all cells.

---

# 📈 Future Improvements

- Hybrid Search (BM25 + Vector Search)
- FAISS support
- Better prompt engineering
- Query expansion
- Metadata filtering
- Streamlit web application
- Docker deployment
- API deployment with FastAPI

---

# 🎓 Learning Outcomes

This project demonstrates practical implementation of:

- Retrieval-Augmented Generation (RAG)
- Semantic Search
- Vector Databases
- Embedding Models
- Cross-Encoder Re-ranking
- Prompt Engineering
- Large Language Models
- Information Retrieval

---

# 📄 License

This project is licensed under the MIT License.

---

# 👤 Author

**Hanaa Khan**

- LinkedIn: *(Add your profile)*
- GitHub: *(Add your GitHub profile)*
