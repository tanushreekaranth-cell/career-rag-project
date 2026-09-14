# career-rag-project
A simple project built using basic tech demo
🎓 CareerRAG — AI Career & Placement Document Assistant

CareerRAG is an AI-powered document assistant that helps students quickly find relevant information from career, internship, and placement documents.

🚀 Features

- 📄 Reads multiple PDF documents
- ✂️ Splits documents into smaller text chunks
- 🧠 Generates semantic embeddings using Sentence Transformers
- 🔎 Performs semantic search using FAISS
- 💬 Provides an easy-to-use Gradio web interface
- 📚 Shows the source PDF for each result

🛠️ Technologies Used

- Python
- PyPDF
- Sentence Transformers
- FAISS
- Gradio

🔄 Project Workflow

PDF Documents
      ↓
Text Extraction
      ↓
Chunking
      ↓
Sentence Transformers
      ↓
Embeddings
      ↓
FAISS Semantic Search
      ↓
Gradio Web Interface

📁 Project Structure

CareerRAG/
│
├── app.py
├── requirements.txt
├── README.md
│
└── Documents/
    ├── placement.pdf
    ├── internship.pdf
    ├── syllabus.pdf
    └── career.pdf

▶️ How to Run

Install the required packages:

pip install -r requirements.txt

Run the application:

python app.py

The application opens through the Gradio web interface.

💡 Example Questions

- What skills are required for placement?
- What are the internship requirements?
- What is the placement eligibility criteria?
- What career opportunities are available?

🎯 Objective

The main objective of CareerRAG is to reduce the time students spend searching through multiple career and placement documents by providing fast semantic document retrieval.

👩‍💻 Project

CareerRAG — AI Career & Placement Document Assistant
