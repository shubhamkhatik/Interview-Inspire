# LLM & RAG Interview Guide

Large Language Models and Retrieval-Augmented Generation systems.

## Key Topics to Cover

- **Prompt Engineering**: Zero-shot, Few-shot, Chain-of-Thought (CoT), Tree of Thoughts, ReAct, Prompt injection defense, Structured outputs (JSON schema / Pydantic).
- **Embeddings & Vector Spaces**: Dense vs Sparse embeddings (BM25 vs OpenAI/Voyage/BGE), Cosine similarity vs Dot product vs Euclidean distance.
- **Vector Databases**: Pinecone, Qdrant, Chroma, Milvus, pgvector; Indexing algorithms (HNSW, IVF-PQ).
- **RAG Architectures**:
  - Chunking strategies (Fixed-size, Recursive, Semantic, Document-aware)
  - Naive RAG vs Advanced RAG vs Modular RAG
  - Query Transformation (Query expansion, Multi-query, HyDE - Hypothetical Document Embeddings)
  - Hybrid Search (BM25 keyword search + Vector dense search + Reciprocal Rank Fusion)
  - Re-ranking (Cross-encoders, Cohere rerank)
  - Context compression & Lost-in-the-middle mitigation
