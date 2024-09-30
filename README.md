

---

# AI-Powered Document Knowledge Extractor

### 🌟 Project Overview
This AI-driven project enables users to:
1. Upload a document (PDF/DOC)
2. Ask AI questions related to the content
3. Generate knowledge graphs to visualize relationships within the document

---

### 🚀 Key Features
- **File Upload**: Supports PDF and DOC formats for document processing.
- **AI-Powered Q&A**: Use advanced Natural Language Processing (NLP) to ask questions about the uploaded document.
- **Knowledge Graphs**: Automatically generate dynamic graphs to represent the document’s key concepts and relationships.

---

### 🛠️ Tech Stack
- **Backend**: Python (Flask/Django/FastAPI)
- **AI**: OpenAI/GPT models, Natural Language Processing (NLP)
- **Document Parsing**: 
  - PDFs: PyMuPDF, pdfplumber
  - DOCs: python-docx
- **Knowledge Graph Generation**: NetworkX, Matplotlib, Graphviz
- **Frontend (if applicable)**: React / Angular / Vue or pure HTML, CSS, JavaScript
- **Database**: SQLite / PostgreSQL (if needed)

---

### 📋 Installation Guide

1. **Clone the repository**  
   `git clone https://github.com/yourusername/yourproject.git`

2. **Navigate to the project directory**  
   `cd yourproject`

3. **Install the dependencies**  
   `pip install -r requirements.txt`

4. **(Optional) Create and activate a virtual environment**  
   `python -m venv venv`  
   `source venv/bin/activate` (on Windows, use `venv\Scripts\activate`)

5. **Run the backend server**  
   `python app.py`

---

### 📊 Usage Steps

1. Run the server and open the web interface or use API endpoints.
2. Upload a document (PDF/DOC).
3. Ask questions about the document.
4. View the generated knowledge graphs that visually represent key insights from the document.

---

### 📡 API Endpoints

1. **POST /upload**  
   Upload a PDF/DOC file for processing.  
   Example request:  
   `curl -X POST -F "file=@yourfile.pdf" http://localhost:5000/upload`

2. **GET /ask**  
   Ask questions about the document.  
   Example request:  
   `curl -X GET "http://localhost:5000/ask?question=What is the main topic?"`

3. **GET /knowledge-graph**  
   Generate a knowledge graph based on the document’s content.  
   Example request:  
   `curl -X GET http://localhost:5000/knowledge-graph`

---

### 🧩 Project Structure

- `static/`: Frontend assets (if applicable)
- `templates/`: HTML templates (if applicable)
- `models/`: AI model scripts and logic
- `utils/`: Utility functions (PDF parsing, graph generation)
- `app.py`: Main backend file
- `requirements.txt`: Project dependencies
- `README.md`: Project documentation

---

### 🔧 Future Enhancements
1. Expand supported document formats (e.g., DOCX, TXT).
2. Improve AI model accuracy.
3. Enhance graph generation with better layouts and more data visualization techniques.
4. Add real-time collaboration features.

---



---

### 🤝 Contributing
Contributions are welcome! Follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Submit a pull request.

---

### ✨ Acknowledgements
- OpenAI GPT models
- PyMuPDF
- NetworkX

---

### 📧 Contact
Feel free to reach out at: aadityashankar21@gmail.com

---

