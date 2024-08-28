# RAG-application
RAG application with LLM, chat history, reranker

For articles.json, I have upload on https://github.com/Wonderofyou/CRAWLVNEXPRESS

1) Data Chunking: Split the articles into smaller, manageable chunks for efficient processing and retrieval.
2) Vector Database: Store the chunked data into a vector database to enable fast and accurate retrieval of relevant documents.
3) Document Retrieval and Reranking: Given a user prompt, retrieve the most relevant documents from the vector database. Combine the prompt with these documents and apply a reranker to identify the top-k most relevant documents.
4) Insight Generation: Use the LLM to generate insights based on the top-ranked documents, enhancing the response with more context and relevance.
