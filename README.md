# Document Compressor Pipeline

## Description
The LLM-Enhanced PDF Knowledge Extractor is an advanced tool designed to process and analyze large collections of PDF documents using state-of-the-art Large Language Models (LLMs). The tool splits text from PDFs into smaller chunks, embeds the chunks using HuggingFace's sentence-transformers, and stores them in a Chroma vector database. The stored embeddings are then queried using various retrieval mechanisms, including contextual compression and filtering, to provide accurate and relevant responses to user queries.

This tool is ideal for tasks such as document indexing, information retrieval, and knowledge management across large document sets.

## Features
PDF Parsing: Automatically loads and parses multiple PDF files from a specified directory.
Text Chunking: Splits parsed text into manageable chunks for efficient processing.
Embeddings Generation: Uses sentence-transformers from HuggingFace to generate high-quality embeddings for each text chunk.
Vector Store Management: Stores and retrieves embeddings using Chroma, a high-performance vector database.
Contextual Compression: Utilizes contextual compression techniques to retrieve the most relevant information from large document sets.
Custom Retrieval Chains: Includes multiple retrieval chains like LLMChainExtractor, LLMChainFilter, EmbeddingsFilter, and DocumentCompressorPipeline for flexible query processing.
