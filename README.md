🎓 PEC Connect
The Ultimate Student Success Portal for Pallavi Engineering College
Python Streamlit AI Engine Database Status

Key Features • Tech Stack • Installation • Structure • Screenshorts

🚀 Overview
PEC Connect is a centralized, AI-powered academic platform tailored for Pallavi Engineering College. It bridges the gap between academic struggles and success by integrating GenAI into the student workflow.

From an AI "Fail-to-Pass" Tutor that explains concepts like you're 5, to a Mock Exam Simulator powered by Groq Llama 3 that mimics JNTUH R24 patterns, this platform is designed to eliminate backlogs and boost GPA.

💎 Key Features
Module	Feature Name	Description	Tech Power
🤖	AI Study Bot	A "Fail-to-Pass" engine. Acts as a strict examiner, diagram artist, and personal tutor. Specialized in JNTUH R24 Syllabus.	Gemini 2.0 Flash
📝	Mock Exam Simulator	Generates instant 5-question MCQs based on previous years' patterns (R18/R22/R24). detailed solutions included.	Groq Llama-3-70b
📚	Notes Marketplace	A peer-to-peer hub for buying and selling high-quality handwritten notes.	SQLite3
📊	Skill Radar	Visualizes student strengths (Python, Math, Logic) using interactive Spider Charts.	Plotly
🎨	Diagram Generator	Instantly draws engineering flowcharts and block diagrams from text descriptions.	Graphviz
👤	Glassmorphism UI	A stunning, modern UI with "Glass" effects, Lottie animations, and a professional dashboard.	CSS3 & Lottie
🛠 Tech Stack
This project leverages the bleeding edge of Open Source AI and Python web frameworks.

Frontend: Streamlit (Python-based UI)
LLM Orchestration:
Groq: For ultra-fast (<1s) Mock Test generation.
Google Gemini: For deep concept explanation and grading.
Database: SQLite (Lightweight, Serverless).
Visuals:
Plotly: For interactive data charts.
Streamlit-Lottie: For vector animations.
Graphviz: For algorithmic diagram generation.
⚡ Installation & Setup
Follow these steps to get the app running on your local machine.

1. Clone the Repository
bash git clone https://github.com/00abhiram/PEC_Connect_Capstone.git cd PEC-Connect

2. Install Dependencies Make sure you have Python installed. Then run:
Bash pip install -r requirements.txt

3. Configure Secrets (Crucial 🔐)
This app requires API keys. Create a secret file:

Create a folder named .streamlit in the root directory.
Create a file named secrets.toml inside it.
Paste your keys: TOML
.streamlit/secrets.toml
GOOGLE_API_KEY = "your_gemini_api_key_here" GROQ_API_KEY = "your_groq_api_key_here"

4. Run the App
Bash streamlit run app.py

📂 Project Structure
Click to expand file tree
Screenshorts
Dashboard
Dashboard

    Modern Glassmorphism UI
AI Study Bot
AI Bot

    Context-Aware R24 Tutor
Mock Tests
Mock Test

    Groq Powered Instant Exams
Profile Radar
Profile

    Performance Analytics
🤝 Contributing
Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

Fork the Project
Create your Feature Branch (git checkout -b feature/AmazingFeature)
Commit your Changes (git commit -m 'Add some AmazingFeature')
Push to the Branch (git push origin feature/AmazingFeature)
Open a Pull Request
📜 License
Distributed under the MIT License. See LICENSE for more information.

Built with ❤️ by the students of Pallavi Engineering College Visit College Website
