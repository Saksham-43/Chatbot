# 🧠 RAG Q&A Chatbot:

A Retrieval-Augmented Generation (RAG) chatbot that answers natural language questions based on structured CSV data using vector search (FAISS) and a Hugging Face transformer model (Flan-T5). Built with LangChain and Hugging Face tools.

**🚀 Features:**

* 🔍 Intelligent document retrieval using FAISS vector store.<br>
* 🤖 Generative answers using google/flan-t5-small (lightweight and offline).<br>
* 📄 Data source: Loan application dataset (Training Dataset.csv).<br>
* 🧠 Embeddings via sentence-transformers (all-MiniLM-L6-v2).<br>
* ⚙️ Easily customizable for other structured CSVs or datasets.<br>

**🛠️ Tech Stack:**

* LangChain for chaining retriever and LLM.<br>
* Hugging Face Transformers (flan-t5-small).<br>
* FAISS for semantic vector search.<br>
* sentence-transformers for embedding text.<br>
* Python, Pandas for data handling.<br>
