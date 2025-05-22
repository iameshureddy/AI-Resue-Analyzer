# 🧠 AI Resume Analyzer
![WhatsApp Image 2025-05-22 at 17 42 01_208dad23](https://github.com/user-attachments/assets/dcb14f72-a008-4653-8089-20df507fb02a)


An intelligent, Streamlit-powered web app that analyzes resumes to extract key skills, match qualifications, and provide AI-powered feedback. Built with Python, this tool helps job seekers and recruiters get fast, meaningful insights from resumes in PDF or DOCX format.

---

## 🚀 Features

- 📄 Upload resumes in PDF or DOCX format
- 🤖 AI-powered resume analysis using GPT or Gemini (optional)
- 🧠 Skill extraction and keyword matching
- 🔐 Optional login system for user authentication
- 📊 Resume history/bookmarking features
- ☁️ Deployable locally or on the cloud (Streamlit Cloud/Render)
- 🌙 Dark mode and modern UI (optional)

---

## 🛠️ Tech Stack

- **Frontend & UI:** Streamlit
- **Backend:** Python
- **AI Integration:** OpenAI / Gemini API (optional)
- **File Handling:** PyPDF2 / python-docx
- **Database (Optional):** SQLite

---

## 📦 Installation

1. **Clone this repository**:

```bash
git clone https://github.com/your-username/ai-resume-analyzer.git
cd ai-resume-analyzer
````

2.Set up a virtual environment (optional but recommended):

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the App Locally

After installing all dependencies:

```bash
streamlit run app.py
```

The app will open in your browser at `http://localhost:8501`.

---

## 🌐 Deployment

### ✅ Deploy on [Streamlit Cloud](https://streamlit.io/cloud)

1. Push this code to your GitHub repository.
2. Go to Streamlit Cloud → Sign in with GitHub.
3. Click **“New App”**, choose your repo and `app.py`.
4. Click **Deploy** – done!

## 📄 requirements.txt (example)


streamlit
pandas
python-docx
PyPDF2
openai
google-generativeai
scikit-learn


## 🧠 Future Enhancements

* ✨ AI-generated feedback and scoring
* 📧 Email integration to send analysis reports
* 📂 Multi-resume bulk analysis
* 📊 Dashboard with visualization of resume stats
* 🔎 Job match percentage based on custom job descriptions

---

## 🙋‍♂️ Contributing

Pull requests are welcome! If you’d like to suggest enhancements or report bugs, open an issue first.

---



