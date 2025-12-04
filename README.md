# 🧠 GenAI Assignment Checker & Feedback Generator

A smart AI-powered tool that evaluates assignments, checks plagiarism, and generates structured feedback using Groq’s Llama models.
Built with Streamlit, Python, and NLP techniques.

# 🚀 Features

AI Evaluation

Grammar score

Coherence score

Structure & creativity scores

Overall score (out of 100)

Summary, improvements, and professional feedback

Plagiarism Checker

Compares assignment with sample essays

Shows highest match percentage

Detects copied content

Multi-File Support

Upload TXT, PDF, or DOCX

Auto-extracts text

Download Feedback

Get full JSON report

Simple & Clean UI

Built using Streamlit

# 🛠️ Tech Stack

Python

Streamlit

Groq Llama 3.1 API

PyPDF2

python-docx

difflib (for similarity matching)

dotenv

# 📂 Project Structure
project-folder/
│
├── newapp.py                
├── sample_essays/       
├── .env                  
├── requirements.txt      
└── README.md            

# 🔑 Setup Instructions
1️⃣ Clone the Repository
git clone [(https://github.com/Saswati-12-git/genai-assignment-checker-feedback-generator)]
cd genai-assignment-checker-feedback-generator

2️⃣ Install Requirements
pip install -r requirements.txt

3️⃣ Add Your Groq API Key

Create a .env file:

GROQ_API_KEY=your_api_key_here


Do NOT share this key publicly.

▶️ Run the App (Locally)
streamlit run app.py


App will open at:
http://localhost:8501

# ☁️ Deploy on Streamlit Cloud

Push your project to GitHub

Open: https://share.streamlit.io

Click New App

Select your repo

Add your API key in:
Settings → Secrets → Add New Secret

GROQ_API_KEY=your_api_key_here


# Deploy 🚀

📊 How It Works (Simple Explanation)

User pastes or uploads an assignment

Script extracts text (txt / pdf / docx)

Cleans and pre-processes the text

Sends it to Groq Llama model for evaluation

Generates:

Scores

Summary

Bullet improvements

Professional feedback

Checks plagiarism using text similarity

Shows matched file & percentage

Allows JSON download

# 📝 Example Output
{
  "grammar_score": 8,
  "coherence_score": 7,
  "structure_score": 8,
  "creativity_score": 6,
  "overall_score": 82,
  "summary": "The writing clearly explains the topic...",
  "suggested_improvements": "- Improve sentence flow\n- Add examples...",
  "feedback": "Good work with strong clarity. Some areas need better coherence."
}

# 🤝 Contributing

Pull requests are welcome!
Open an issue for suggestions or bug fixes.

# 📄 License

This project is under the MIT License.

# ⭐ Support

If you find this project helpful, please star the repo on GitHub ⭐😊
