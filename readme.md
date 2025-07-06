# NVIDIA NIM RAG Streamlit App

🚀 A Retrieval-Augmented Generation (RAG) app using NVIDIA NIM’s LLaMA3-70B Instruct model to answer questions from PDF documents. Built with LangChain and FAISS for vector search and deployed via Streamlit.

---

## 💡 Features

✅ Loads PDFs for knowledge ingestion  
✅ Splits documents into chunks for embedding  
✅ Uses NVIDIA’s NIM endpoint for fast, high-quality answers  
✅ Performs vector similarity search using FAISS  
✅ Simple Streamlit interface

---

## 🔧 Requirements

- Python 3.10+
- NVIDIA NIM API Key

Install dependencies:

```bash
pip install -r requirements.txt

streamlit
python-dotenv
langchain
langchain-core
langchain-community
langchain-nvidia-ai-endpoints
langchain-huggingface


🔑 Environment Variables

save this in a .env:

NVIDIA_API_KEY=nvapi-xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx

🗂 Project Structure

nvidia-nim-rag-streamlit-app/
│
├── app.py
├── requirements.txt
└── README.md


🚀 How to Run

Run your Streamlit app locally:

streamlit run app.py

🎯 Usage

Click Documents Embedding to load and vectorize your PDFs.

Enter a question in the input box.

Get an accurate answer from NVIDIA’s LLaMA3-70B model!

Example question:

Summarize the main topics covered in the uploaded research papers.
