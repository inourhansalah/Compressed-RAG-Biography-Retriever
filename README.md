# Compressed-RAG Biography Retriever

A local Retrieval-Augmented Generation (RAG) pipeline using **LangChain**, **Ollama**, and **ChromaDB** to compress and retrieve relevant answers from a biography document. This setup demonstrates local LLM-based question answering with compressed context retrieval.

---

##  Features

- **Local LLMs with Ollama**  
  Uses the `gemma3:27b` model served locally via Ollama.

- **Embedding Generation**  
  Uses `nomic-embed-text` model to generate document embeddings locally.

- **Document Chunking & Storage**  
  Splits a biography into chunks and stores embeddings in ChromaDB.

- **Context Compression**  
  Retrieves and compresses relevant context using `LLMChainExtractor`.

- **RAG-style Q&A**  
  Answers specific questions about the document using retrieved context.

---

##  Tools & Libraries

| Tool/Library         | Purpose                                      |
|----------------------|----------------------------------------------|
| **LangChain**        | Orchestration of LLM workflows               |
| **Ollama**           | Serve local LLMs and embedding models        |
| **ChromaDB**         | Local vector store for semantic search       |
| **LangChain Community** | Access to additional LangChain modules   |
| **TextLoader**       | Load local documents                         |
| **CharacterTextSplitter** | Chunking text with overlap             |
| **ContextualCompressionRetriever** | Smart context filtering       |
| **LLMChainExtractor** | Compresses documents via LLM inference      |

---

