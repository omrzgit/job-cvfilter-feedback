# 💼 JOBIEE AI Job Filter & Mock Interview Coach

JOBIEE is an intelligent career assistant and AI mock interview platform built with **Streamlit**, **OpenAI GPT**, and **FPDF**. It helps candidates find matching corporate openings based on their education and seniority, extract insights from their CV/resume, generate dynamic role-tailored interview challenges, evaluate responses in real-time, and download professional PDF evaluation scorecards.

---

## ✨ Features

- **🎨 Modern & Responsive UI**: Clean visual design with custom CSS, interactive progress stepper, pill tags, metric cards, and responsive layout.
- **🔍 Smart Role Matching**: Matches candidates to open roles based on degree level (*Undergraduate, Graduate, Post Graduate*), seniority (*Junior, Senior*), and field of study.
- **📄 Resume / CV Parsing**: Upload PDF, DOCX, or TXT resumes for customized AI interview context.
- **🤖 Tailored AI Mock Interviews**: Dynamically generates coding, conceptual, and situational questions tailored to the company's job description and candidate background.
- **📊 Real-Time Feedback & Scoring**: Instant grading (1–10) and actionable strengths/weaknesses feedback for each submitted response.
- **📑 Downloadable PDF Scorecard**: Generates an interview transcript with performance analytics and downloadable PDF report.
- **⚙️ Configurable AI Engine**: In-app OpenAI API key input and model selector (`gpt-3.5-turbo`, `gpt-4o-mini`, `gpt-4o`).

---

## 🚀 Quick Start

### 1. Clone the repository
```bash
git clone https://github.com/AKM-13/job-filter-chatbot.git
cd job-filter-chatbot
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Set OpenAI API Key (Optional)
You can set your OpenAI API key in your environment or enter it directly in the app sidebar:
```bash
export OPENAI_API_KEY="your-api-key-here"  # Linux / macOS
set OPENAI_API_KEY=your-api-key-here     # Windows CMD
$env:OPENAI_API_KEY="your-api-key-here"   # Windows PowerShell
```

### 4. Run the application
```bash
streamlit run JOBIEE.py
```

---

## 📂 Project Structure
```
job-filter-chatbot/
├── JOBIEE.py          # Main Streamlit application & AI logic
├── requirements.txt   # Python package dependencies
└── README.md          # Documentation & Setup guide
```
