# 📄 Chat with Your PDFs: AI-Powered Document Interaction

This project is a Streamlit application that allows users to upload PDF documents and interact with their content by asking questions and receiving detailed, context-aware answers. The app leverages the power of Google's Gemini API to provide accurate and relevant responses based on the text within the uploaded PDFs.

## 🌟 Features

- **PDF Upload:** Users can upload one or more PDF files.
- **Text Extraction:** The app extracts text from each uploaded PDF.
- **Text Chunking:** The extracted text is split into manageable chunks for better processing.
- **Vector Storage:** The text chunks are embedded into a vector store using Google Generative AI Embeddings.
- **AI-Powered Q&A:** Users can ask questions, and the app retrieves the most relevant text chunks to provide accurate answers.
- **Real-Time Interaction:** Immediate response generation, allowing seamless interaction with PDF content.

## 🛠️ How It Works

1. **Upload PDFs:** Users upload their PDF files via the sidebar menu.
2. **Text Processing:** The app extracts text from the PDFs and splits it into chunks.
3. **Vector Storage:** The text chunks are stored in a vector database using embeddings from the Gemini API.
4. **Ask Questions:** Users input their questions, which are processed to find the most relevant text chunks.
5. **AI Response:** The Gemini API is used to generate detailed answers based on the context from the extracted text.

## 🚀 Getting Started

### Prerequisites

- Python 3.x
- Streamlit
- PyPDF2
- LangChain
- Google Generative AI API
- FAISS (Facebook AI Similarity Search)
- dotenv

