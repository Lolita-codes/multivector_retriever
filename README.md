# Multivector Retriever
An efficient and accurate retrieval of relevant information from large and diverse datasets by leveraging both summarized representations (for quick matching) and full data (for comprehensive answers). 

## Project Objective
This retriever is used in the Multi-representation indexing, a RAG retrieval approach. When a question is posed, the system uses the embedding stored in the vectorstore to find the most relevant content. The corresponding full document, table, or image is then retrieved from the Docstore, providing the user with detailed information that matches their query.

## Technologies Utilized
- Python  
- LangChain  
- Cohere  
- Chroma Database  
- In-Memory Byte Storage  

## Methods Utilized
- Data Collection: Used web scraping tools to load content from specific URLs.   
- Summarization: Used LLM to generate short summaries of each document.  
- Vectorization and Embedding: Used document embeddings to represent summaries as vectors, enabling similarity searches.  
- Retrieval: Integrated a multi-vector retriever to fetch and rank documents based on semantic similarity to a query.  
