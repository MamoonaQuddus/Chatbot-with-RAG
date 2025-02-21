# AI Chatbot

## 📌 Overview
AI Chatbot is a Streamlit-based application that enables users to interact with an AI-powered chatbot capable of answering questions based on uploaded documents (PDF, DOCX, TXT). It leverages Groq's AI models and LangChain for document processing and retrieval-based question answering.

## 🚀 Features
- **File Upload:** Supports PDF, DOCX, and TXT files.
- **AI-Powered Chat:** Uses Groq AI to provide intelligent responses.
- **Document-Based Q&A:** Answers questions based on uploaded files.
- **Custom Styling:** Loads external CSS for a better UI.
- **Secure API Key Input:** Users can input their API keys safely.

## 🛠️ Tech Stack
- **Python**
- **Streamlit** (UI framework)
- **LangChain** (AI model integration)
- **HuggingFace Embeddings** (Vector store)
- **Groq API** (AI processing)
- **PyPDFLoader, Docx2txtLoader, TextLoader** (Document processing)

## 📥 Installation
### 1. Clone the Repository
```sh
 git clone https://github.com/MamoonaQuddus/Chatbot-with-RAG.git
 cd Chatbot-with-RAG
```

### 2. Create a Virtual Environment (Optional but Recommended)
```sh
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

### 3. Install Dependencies
```sh
pip install -r requirements.txt
```

### 4. Run the Application
```sh
streamlit run app.py
```

## 🔑 Usage
1. Enter your **Groq API Key** in the sidebar.
2. Upload a **PDF, DOCX, or TXT** file.
3. Type a question in the chat input field.
4. View AI-generated responses with source references.

## 📝 Future Enhancements
- Add support for multiple AI models.
- Improve document chunking for better retrieval.
- Enhance UI with more interactive elements.

## 👨‍💻 Author
Developed by **Mamoona Quddus known as Error Girl 👩‍💻**

## 📜 License
This project is licensed under the MIT License.

