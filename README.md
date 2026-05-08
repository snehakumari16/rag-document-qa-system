RAG Based Document QA System

Research Project by Sneha Kumari J
B.Tech Artificial Intelligence & Machine Learning | Presidency University, Bengaluru

---

Overview
A Retrieval Augmented Generation (RAG) system that combines 
semantic search with Large Language Models to answer questions 
accurately from documents, significantly reducing hallucination.

---

 System Architecture
Document → Chunking → Embeddings → FAISS Vector DB
                                          ↓
Question → Embedding → Similarity Search → Relevant Chunks
                                          ↓
                              LLaMA + Context → Grounded Answer

---

 Modules

Module 1 — Document Processing
- Text chunking with overlapping windows
- Preserves context across chunk boundaries

 Module 2 — Vector Database
- Sentence Transformers for embeddings
- FAISS index for fast similarity search
- Top-K relevant chunk retrieval

 Module 3 — RAG QA Pipeline
- Context-grounded question answering
- LLaMA 3.1 via Groq API
- Hallucination reduction through retrieval

 Module 4 — RAG vs No RAG Comparison
- Side by side comparison
- Demonstrates grounding effectiveness
- Shows hallucination reduction

---

Tech Stack
- Python
- Groq API + LLaMA 3.1 8B
- Sentence Transformers (MiniLM)
- FAISS Vector Database
- PyPDF2

---

Key Findings
1. RAG reduces hallucination significantly
2. Chunk overlap preserves contextual information
3. Semantic search retrieves more relevant chunks than keyword search
4. Context grounding improves factual accuracy

---

 Research Relevance
- Grounded text generation
- LLM hallucination mitigation
- Information retrieval systems
- Knowledge base QA
- Practical LLM applications

---

Author
Sneha Kumari J
- LinkedIn: https://www.linkedin.com/in/sneha-kumari-computer-engineering
- Email: snehakumari1869@gmail.com
