# Retrievers_in_RAG
A retriever in RAG is like a smart search helper. When you ask a question, the retriever looks through your documents and finds the most relevant pieces of information. The LLM then uses those retrieved pieces to answer your question more accurately.

🖼️ Diagram: Where the Retriever Fits in RAG

User Question
      │
      ▼
 ┌─────────────┐
 │   Retriever │  ← searches your documents
 └─────────────┘
      │  top-k relevant chunks
      ▼
 ┌─────────────┐
 │     LLM     │  ← uses chunks + question
 └─────────────┘
      │
      ▼
  Final Answer
