AI College Assistant

Project Overview

The AI College Assistant is an AI-powered academic information chatbot developed using Retrieval-Augmented Generation (RAG).

It helps students find information about college rules, attendance policies, examinations and college events using uploaded PDF documents.

The application retrieves relevant information from a knowledge base and uses Google's Gemini LLM to generate contextual answers.

Objectives

- Develop an AI-powered academic assistant.
- Extract information from college PDF documents.
- Create a searchable knowledge base.
- Retrieve relevant information using semantic search.
- Generate contextual answers using Gemini.
- Display responses with document references.

Technologies Used

- Python
- Google Colab
- Gemini API
- Sentence Transformers
- FAISS
- PyMuPDF
- NumPy
- Gradio

 Project Workflow

1. PDF document upload.
2. Text extraction using PyMuPDF.
3. Text chunking.
4. Embedding generation using Sentence Transformers.
5. Vector storage using FAISS.
6. Semantic search and information retrieval.
7. Answer generation using Gemini.
8. Chatbot interface using Gradio.

Architecture

PDF Documents → Text Extraction → Chunking → Embeddings → FAISS Vector Database → Semantic Retrieval → Gemini LLM → Answer Generation → Gradio Chatbot.

How to Run

1. Open the notebook in Google Colab.
2. Install the required libraries.
3. Add your Gemini API key to Google Colab Secrets using the name `GEMINI_API_KEY`.
4. Upload the required PDF documents.
5. Execute the notebook cells in order.
6. Launch the Gradio chatbot.

Security

Never upload API keys, passwords, personal student information or unauthorized college documents.

Future Enhancements

- OCR for scanned documents.
- Improved semantic retrieval.
- Conversation history.
- Better source-grounded citations.
- Secure authentication.

 Project Status

Prototype – Under Development.

 Disclaimer

This is an academic project prototype. Sample documents and institutional policies must be verified and authorized before real-world use.
