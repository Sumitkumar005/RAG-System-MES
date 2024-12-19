# RAG System for MES (Manufacturing Execution System)

This repository contains the code for a **Retrieval-Augmented Generation (RAG)** system designed for a **Manufacturing Execution System (MES)** in the **chemical industry**. The goal is to create a knowledge base that can answer user queries by retrieving relevant information from multiple data sources such as text documents, video/audio transcripts, structured logs, and images.

## Project Overview

The system performs the following tasks:
1. **Data Ingestion**: Collect data from various sources (text, video, audio, images).
2. **Data Preprocessing**: Clean and format the data for model processing.
3. **Embedding Generation**: Generate embeddings for the data using pre-trained models.
4. **Vector Database**: Store the embeddings in a vector database for fast retrieval.
5. **RAG Workflow**: Process user queries by retrieving relevant documents and generating responses using a language model (e.g., GPT-4).
6. **Deployment**: The solution is deployed as a Streamlit app for easy interaction.

## System Architecture

The system architecture consists of the following components:
- **Data Collection & Preprocessing**: Handling text, audio, video, and image data.
- **Embedding Generation**: Using models like Sentence-BERT to generate embeddings for text, and CNN-based models for images.
- **Vector Database**: Using Pinecone (or Milvus) to store and query embeddings.
- **RAG Pipeline**: A seamless workflow for retrieval and response generation.
- **Streamlit Application**: For deployment and interaction.

[Include Architecture Diagram Here]

## Requirements

To run the project locally, you'll need the following libraries:
- Python 3.8+
- Install required dependencies by running:
  ```bash
  pip install -r requirements.txt
