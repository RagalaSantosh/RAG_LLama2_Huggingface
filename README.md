**RAG System Using Llama2 With Hugging Face**
This repository contains the implementation of a **Retrieve and Generate (RAG)** system using the **Llama2 model** with the Hugging Face library. The purpose of this system is to process and generate information from PDF documents. Here are the key components and steps involved:

**Installation Setup:**
Begin by installing the necessary Python packages to set up the environment:
**!pip install -r requirements.txt**


**Python Code Breakdown:**

The core script for setting up the RAG system is detailed below, outlining each step in the process:
1. **Loading Documents:** Use SimpleDirectoryReader to load the documents that will be indexed.
2. **System Prompt Setup:** Define a system prompt to guide the Q&A assistant’s responses.
3. **Query Wrapper Prompt:** Format the queries using SimpleInputPrompt.
4. **Hugging Face Integration:** Set up the Llama2 model with the Hugging Face API.
5. **Embedding Model and Service Context:** Establish the embedding model and service context for processing the documents.
6. **Index Creation and Query Engine:** Build an index from the documents and set up a query engine for response generation.
7. **Queries and Responses:** Query the index for specific questions and print the responses, demonstrating the RAG system’s capability to retrieve and generate information based on indexed data.
   
**Conclusion:**
This script encapsulates the journey from setting up the necessary environment and libraries to querying an index with a sophisticated language model. It exemplifies how to harness the power of Llama2 and Hugging Face for building a RAG system, demonstrating the advanced potential of modern language models in information processing and generation.
