# 🎓 PEC Connect
### The Ultimate AI-Powered Student Success Portal for Pallavi Engineering College

[Key Features](#-key-features) • [Tech Stack](#-tech-stack) • [Installation](#-installation--setup) • [System Architecture](#-project-structure) • [Contributing](#-contributing) • [License](#-license)

---

## 🚀 Overview
**PEC Connect** is an enterprise-grade, centralized academic platform engineered specifically for **Pallavi Engineering College**. The application addresses critical academic bottlenecks by natively integrating low-latency Generative AI models directly into the student workflow. 

By pairing an AI "Fail-to-Pass" tutoring engine strictly mapped to the **JNTUH R24 Syllabus** alongside a high-concurrency Mock Exam Simulator built for tracking evaluation patterns, the platform aims to systematically close academic comprehension gaps, mitigate backlogs, and maximize student cumulative GPA.

---

## 💎 Key Features

| Module | Feature Name | Core Functionality | Technical Backing |
| :--- | :--- | :--- | :--- |
| **🤖** | **AI Study Bot** | A contextual "Fail-to-Pass" engine acting as an examiner, concept breakdown expert, and personal tutor matching JNTUH criteria. | Gemini 2.0 Flash |
| **📝** | **Mock Exam Simulator** | Compiles real-time 5-question multi-choice mock assessments tailored to historical **R18 / R22 / R24 patterns** with instant solution breakdowns. | Groq Llama-3-70b |
| **📚** | **Notes Marketplace** | Secure, serverless peer-to-peer data hub designed for listing, hosting, and tracking high-quality handwritten student notes. | SQLite3 Relational Engine |
| **📊** | **Skill Radar** | Accumulates telemetry on academic strengths (Python, Mathematics, Logic) to compute complex mathematical multi-axis data point maps. | Plotly Core Engine |
| **🎨** | **Diagram Generator** | Procedurally renders technical engineering flowcharts and structural software block designs from raw input text strings. | Graphviz Compiler |
| **👤** | **Glassmorphism UI** | A premium, modern administrative layout built with custom web styling rules, translucent panel layers, and fluid runtime animations. | CSS3 & Lottie Elements |

> 💡 *Note: The overall architecture spans **14 core features**, integrating built-in peer-to-peer mentorship structures, academic failure risk forecasting pipelines, and a student interview experience database.*

---

## 🛠️ Tech Stack

The application layers utilize efficient, open-source AI orchestration patterns combined with low-overhead file system storage:

* **Frontend & UI Layer:** Streamlit (Python-based reactive state machine framework) with structural HTML5/CSS3 interface overrides.
* **LLM Orchestration Layer:**
  * **Groq SDK:** Handles accelerated execution loops for lightning-fast ($<1\text{s}$) multi-model test generation pipelines.
  * **Google GenAI SDK:** Manages deep semantic prompt engineering and precise student solution evaluation logic.
* **Database Management:** SQLite3 (Lightweight, local transactional relational database engine).
* **Data Visualization & Analytics Core:**
  * **Plotly:** Handles programmatic generation of interactive competency radar charts.
  * **Graphviz:** Compiles abstract text data into clean algorithmic engineering layouts.
  * **Streamlit-Lottie:** Houses lightweight vector asset graphics natively through JSON streams.

---

## ⚡ Installation & Setup

Execute these sequential instructions inside your development terminal to clone and configure the system runtime environment locally.

### 1. Clone the Active Project Repository
```bash
git clone [https://github.com/00abhiram/PEC_Connect_Capstone.git](https://github.com/00abhiram/PEC_Connect_Capstone.git)
cd PEC-Connect
