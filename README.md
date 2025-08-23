# 📄 AI Resume Analyzer

📌 An AI-powered tool that scans and analyzes resumes (PDF/DOCX) and gives a score based on keywords, skills, and job description matching.

---

## 🚀 Features
- Upload resumes (PDF/DOCX)  
- Extract text using NLP  
- Match against job description  
- Give a score and feedback  
- User-friendly interface  

---

## 🛠️ Tech Stack
- Backend: **Flask (Python)**  
- NLP: **Spacy / NLTK**  
- File Parsing: **PyPDF2 / python-docx**  
- Frontend: HTML, CSS, Bootstrap  

---

## 📂 Project Structure
📁 ai-resume-analyzer
┣ 📂 templates/ # HTML templates
┣ 📂 static/ # CSS, JS, images
┣ 📜 app.py # Flask main file
┣ 📜 requirements.txt # Dependencies
┗ 📜 README.md

---

## ▶️ How to Run

### 1. Clone the repo
```bash
git clone https://github.com/mohamedkh404/ai-resume-analyzer.git
cd ai-resume-analyzer
2. Install dependencies
pip install -r requirements.txt
pip install flask spacy nltk pypdf2 python-docx
3. Run app
python app.py
4. Open in browser
http://127.0.0.1:5000/
