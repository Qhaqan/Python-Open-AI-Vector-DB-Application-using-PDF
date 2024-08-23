# Python-Open-AI-Vector-DB-Application-using-PDF

Pinecone Vector DB with OpenAI Embeddings and PDF Reader
This repository demonstrates the use of Pinecone as a vector database integrated with OpenAI embeddings, leveraging PdfReader for reading and processing PDF documents. The application is showcased using the Indian 2024 budget PDF as an example.

Features
Vector Database Integration: Utilizes Pinecone for storing and querying vector embeddings.
OpenAI Embeddings: Employs OpenAI's powerful embeddings for accurate and meaningful vector representation of text data.
PDF Processing: Uses PdfReader to extract and process text from PDF files.
Real-world Example: Demonstrates the application using the Indian 2024 budget PDF, showcasing how budget-related information can be embedded, stored, and queried efficiently.
How It Works
PDF Reading: The Indian 2024 budget PDF is read using PdfReader to extract the textual content.
Text Embedding: The extracted text is converted into vector embeddings using OpenAI's embedding model.
Vector Storage: The embeddings are stored in Pinecone's vector database for efficient querying and retrieval.
Querying: You can query the database with natural language prompts to retrieve relevant sections from the budget document.
Requirements
Python 3.x
Pinecone
OpenAI
PdfReader
