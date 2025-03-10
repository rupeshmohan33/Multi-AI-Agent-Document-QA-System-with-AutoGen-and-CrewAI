# AI-Powered Multi-Agent Document Q&A System

## Overview
This project implements an AI-powered **multi-agent document Q&A system** using **AutoGen, LangChain, and CrewAI**. The system allows users to upload documents and ask questions, with AI agents handling verification, retrieval, answer generation, and validation.

## Features
- **Multi-Agent Collaboration:** Utilizes AutoGen and CrewAI to create structured agent workflows.
- **Intelligent Question Handling:** A Question Verification Agent checks the relevance of queries.
- **Efficient Retrieval:** Uses **LangChain & ChromaDB** to fetch the top relevant document chunks.
- **LLM-Powered Answer Generation:** Employs **Llama2/Mixtral-8x7B** for response synthesis.
- **Validation & Feedback:** Ensures accuracy with validation agents and user feedback integration.

## System Workflow
1. **Document Processing**: PDFs are loaded and split into chunks using **LangChain**.
2. **Question Verification**: Determines if a query is relevant.
3. **Document Retrieval**: Retrieves top 3 relevant chunks using **ChromaDB**.
4. **Answer Generation**: LLM processes retrieved data and formulates a response.
5. **Validation & Feedback**: Human feedback refines responses and improves system accuracy.

## Tech Stack
- **AutoGen** (for multi-agent communication)
- **CrewAI** (for structured task delegation)
- **LangChain** (for document processing)
- **ChromaDB** (for vector-based document retrieval)
- **LLMs** (Llama2, Mixtral-8x7B for response generation)
- **Sentence Transformers** (for embedding-based similarity search)

## Installation & Setup
1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo.git
   cd your-repo
   ```
2. Install dependencies:
   ```sh
   pip install autogen crewai langchain chromadb sentence-transformers
   ```
3. Run the system:
   ```sh
   python main.py
   ```

## Deployment
The system can be deployed on:
- **Docker**: For containerized deployment
- **FastAPI**: To serve as an API endpoint
- **Streamlit**: For a user-friendly UI

## Future Improvements
- Integration with **RAG pipelines** for enhanced retrieval.
- Fine-tuning LLMs for better domain-specific accuracy.
- Adding **speech-to-text** capabilities for voice-based queries.

## License
This project is licensed under the MIT License.

## Author
Developed by **Mahankali N V R Pavan Sai Mohan** 🚀

