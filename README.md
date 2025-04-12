# 🤖 Personal RAG Chatbot

**Personal RAG Chatbot** is a multilingual Retrieval-Augmented Generation (RAG) system developed to provide intelligent, context-aware responses based on personalized datasets.

Built using **Streamlit** and the **OpenAI API**, the chatbot supports **Persian 🇮🇷**, **English 🇬🇧**, and **French 🇫🇷**, and is capable of answering academic and personal queries by retrieving and synthesizing information from private sources, including tweets, MSc thesis documents, and user-uploaded files (PDF, DOCX).

Key features include multilingual translation, personalized information retrieval, dynamic file uploads, and a PhD interview simulation module.  
The system emphasizes **data privacy** by keeping personal datasets hidden during public deployment.

---

## 🚀 Features

- **Multilingual Assistance**: Supports Persian 🇮🇷, English 🇬🇧, and French 🇫🇷.
- **Personalized Responses**: Based on tweets, thesis, and user-uploaded documents.
- **RAG (Retrieval-Augmented Generation)**: Intelligent context retrieval and answer generation.
- **PhD Interview Simulation**: Formal academic Q&A session.
- **Dynamic File Upload**: Upload and process PDF or DOCX files during runtime.
- **Data Privacy**: Private datasets are securely managed and not exposed publicly.

---

## 🛠️ Technologies Used

- [Streamlit](https://streamlit.io/) — Web application framework
- [OpenAI API](https://platform.openai.com/) — Language model APIs
- [FAISS](https://github.com/facebookresearch/faiss) — Vector similarity search
- [LangDetect](https://pypi.org/project/langdetect/) — Language detection
- [PyMuPDF](https://pymupdf.readthedocs.io/) — PDF reading
- [python-docx](https://python-docx.readthedocs.io/) — DOCX reading

---

## 📄 How to Run Locally

```bash
# Clone the repository
git clone https://github.com/your-username/personal-rag-chatbot.git

# Navigate into the project directory
cd personal-rag-chatbot

# Install dependencies
pip install -r requirements.txt

# Run the app
streamlit run app.py

