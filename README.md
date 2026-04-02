# 🚀 AI Candidate Screening System (LangGraph)

## 📌 Overview
This project is an AI-powered candidate screening system built using **LangGraph** and **LLMs**.

It analyzes job application text and automatically:
- Categorizes candidate experience level
- Evaluates skill match
- Decides next hiring step

---

## ⚙️ Tech Stack
- Python
- LangChain
- LangGraph
- Google Gemini (or OpenAI)
- dotenv

---

## 🧠 Workflow

1. **Categorize Experience**  
2. **Assess Skillset**  
3. **Decision Routing**:
   - ✅ Schedule HR Interview  
   - ⚠️ Escalate to Recruiter  
   - ❌ Reject Application  

---

## 🔁 Graph Flow

START → categorize_experience → assess_skillset → decision → END

---

## 📂 Project Structure
ai-candidate-screening/
│
├── Recruitment.ipynb # Main notebook
├── requirements.txt
├── .gitignore
├── README.md


---

## 🚀 How to Run

### 1. Clone Repository


```bash
git clone https://github.com/your-username/repo-name.git
cd repo-name
2. Install Dependencies
pip install -r requirements.txt
3. Create .env File

Create a .env file in the root directory and add:

GOOGLE_API_KEY=your_api_key
4. Run Notebook
jupyter notebook

Open:

Recruitment.ipynb
💡 Example Input
"I have 10 years of experience in software engineering with expertise in JAVA"
📤 Example Output
Experience Level: Senior-level
Skill Match: Match
Decision: HR Interview
🔥 Features
LangGraph workflow-based AI system
Conditional decision routing
LLM-powered reasoning
Visual graph representation
🚀 Future Improvements
Resume parsing (PDF support)
RAG-based candidate evaluation
Streamlit UI dashboard
Multi-agent hiring pipeline
⚠️ Important Notes
Do NOT upload your .env file
Keep your API keys secure
👨‍💻 Author

Aakash Harwani