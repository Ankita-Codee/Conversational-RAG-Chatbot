# Conversational RAG Chatbot

## About the Project
This project is a chatbot built using the **Gemini LLM** integrated with **Retrieval-Augmented Generation (RAG)**. It combines the capabilities of a large language model with a document retriever to provide accurate, context-aware responses. The chatbot supports multi-turn conversations by maintaining and storing session-based histories.

Documents are indexed in a vector database, enabling the chatbot to retrieve and reference external knowledge effectively.

---

## Why RAG?
RAG enhances the chatbot by:
- **Improving Accuracy**: Combines LLMs with document retrieval for data-driven responses.
- **Providing Explainability**: Allows the model to cite specific documents as sources.
- **Supporting Scalability**: Handles large knowledge bases efficiently through vector search.

---

## Features
- **Gemini LLM**: Utilizes Google's advanced language model for high-quality responses.
- **Context-Aware Conversations**: Stores and uses chat histories to maintain context across multiple interactions.
- **Document Retrieval**: Incorporates a vector database for precise document-based querying.
- **Session Management**: Tracks conversations using unique session IDs and persistent history storage.

---

## Setup Instructions
1. **Create API Keys**:
   - **LangChain**: Sign up at [LangChain](https://www.langchain.com) and generate an API key.
   - **Google API**: Obtain an API key for Google services and enable the required APIs.

2. **Add Your Documents**:
   - Index your documents in a vector database like **Chroma** or **Pinecone**.
   - Example link for documents: [Dataset Link](https://lilianweng.github.io/posts/2023-06-23-agent/).

---

## How It Works
- **RAG Framework**: Combines retrieval and generation to produce grounded responses.
- **History Storage**: Chat history is managed using `RunnableWithMessageHistory`, enabling context-aware interactions.
- **Chatbot Creation**: The Gemini LLM is integrated with LangChain to provide a seamless conversational experience.

---

