# 🧠 Chat with PDF
Upload your PDF and chat with an LLM that provides answers based on your document.

---

## 📚 Mini LLM with RAG Pipeline

A small **LLM-powered chatbot** that allows users to upload PDFs and ask questions.  
The system retrieves relevant content from the PDF using **embeddings + vector search**, and generates contextual answers using a **Groq-hosted LLM**.

---

## 📖 Overview
This project demonstrates how to build a **Retrieval-Augmented Generation (RAG)** pipeline for document-based Q&A.

### Workflow:
1. User uploads a PDF file.  
2. Text is split into chunks and converted into embeddings.  
3. Embeddings are stored and searched using **Pinecone**.  
4. The query is compared with relevant chunks.  
5. **Groq LLM API** generates a contextual and accurate response.  
6. Answers are displayed through a clean **Streamlit UI**.  

---

## ⚙️ Tools & Technologies
- **LLM**: Groq API (Chat model)  
- **Embeddings**: Cohere Multilingual (dim=1024)  
- **Vector Database**: Pinecone  
- **Frontend/UI**: Streamlit  
- **Language**: Python 3.9+  

---

## ✨ Features
- Upload and interact with your PDFs.  
- Multilingual support via Cohere embeddings.  
- Fast and efficient document search with Pinecone.  
- Simple and interactive **Streamlit interface**.  

---

## 🚀 How to Run
```bash
# Clone the repository
git clone https://github.com/RashiMagar/Chat_with_pdf.git
cd Chat_with_pdf

# Install dependencies
pip install -r requirements.txt

# Run the Streamlit app
streamlit run app.py
```

---

## 👩‍💻 Author
Developed by **Rashi Magar**  
Feel free to fork, use, and improve this project!

---
