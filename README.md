# DocuMentor
Overview
This project implements a custom AI chatbot designed to answer queries related to Islamic law. It utilizes a Retrieval Augmented Generation (RAG) approach to provide accurate and contextually relevant responses based on a document you provide.  The chatbot processes the document as follows:

Load PDF: The document containing Islamic legal texts is loaded.

Split Text: The text is divided into smaller, manageable chunks.

Create Embeddings: Text embeddings are generated for each chunk.

Store in Vector Database: The embeddings are stored in a vector database (FAISS) for efficient retrieval.

Retrieve Context: When a user asks a question, the relevant text chunks are retrieved from the vector database.

Define LLM Pipeline: A pipeline is set up using a Large Language Model (LLM).

Integrate LLM and Retriever: The retrieved context is combined with the user's query and fed to the LLM.

Generate Response: The LLM generates an answer based on the provided context.

Enable Chat History: The chatbot maintains a history of the conversation.

This project leverages the following technologies:

LangChain: A framework for developing applications powered by language models.

Llama 2b: A Large Language Model used for text generation.

FAISS: A library for efficient similarity search and clustering of dense vectors, used as the vector database.

Features
Provides answers to questions about Islamic law based on a user-provided document.

Uses Retrieval Augmented Generation (RAG) for accurate and contextually relevant answers.

Implements chat history to maintain context in ongoing conversations.

Uses Llama 2b for LLM text generation.

Uses FAISS for efficient vector storage and retrieval.
