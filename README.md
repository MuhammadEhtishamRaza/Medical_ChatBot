# Medical ChatBot: A Retrieval-Augmented Generation (RAG) System

🚀 Overview:

The Medical ChatBot is a conversational AI system that leverages Retrieval-Augmented Generation (RAG) to provide accurate medical information. The system retrieves relevant medical documents stored and generates responses using the api of GEMINI models.

🧠 Key Features:

Medical Knowledge Base: A medical documents is used as the knowledge base for retrieval.

Embedding Generation: Converts medical PDF documents into text, clean the extracted text, splits them into smaller chunks, and generates embeddings using Gemini model api.

ChromaDb: The generated embeddings are stored in vector database named ChromaDb.

Retrieval-Augmented Generation (RAG): The chatbot retrieves results for the user queries from the embeddings of the medical documents stored in chromaDB, then uses an Gemini model to generate a response based on the retrieved content.
