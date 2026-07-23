<div align="center">

# Welcome to My Digital Space

[![Amogh's Tech Stack](https://raw.githubusercontent.com/amoghvijay/amoghvijay/main/tech-stack.svg)](https://raw.githubusercontent.com/amoghvijay/amoghvijay/main/tech-stack.svg)

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=24&duration=3000&pause=1000&color=1F6FEB&center=true&vCenter=true&width=560&height=50&lines=Agentic+AI+Developer;Automating+with+AI+everyday;3rd+Year+CSE-AI+Student;Building+AI+agents+that+think+%26+act)](https://git.io/typing-svg)

<a href="https://www.linkedin.com/in/amogh-vijay-151164333" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>
<a href="mailto:amoghvijay07@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"></a>
<a href="https://github.com/amoghvijay" target="_blank"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a>

![Profile Views](https://komarev.com/ghpvc/?username=amoghvijay&color=1f6feb&style=for-the-badge&label=PROFILE+VIEWS)

</div>

---

## 🙋‍♂️ About Me

<table>
<tr>
<td width="60%">

Hey there! I'm a passionate 3rd-year B.Tech CSE (AI) student who loves building AI-powered applications and automating real workflows — not just toy demos.

```javascript
const amogh = {
    location:   "Jaipur, Rajasthan, India",
    education:  "B.Tech CSE – Artificial Intelligence | 3rd Year",
    role:       "Agentic AI Developer",
    philosophy: "Build it once, automate it forever.",

    currently: {
        building:  ["AI Agents with Tool-Calling", "Full Stack AI Apps"],
        learning:  ["Machine Learning", "Deep Learning", "Generative AI"],
        exploring: ["Agentic AI Workflows", "Prompt Engineering"]
    }
};
```

</td>
<td width="40%" align="center">

<img src="https://i.pinimg.com/originals/c0/7a/0e/c07a0e54601516dbf8b399832636507a.gif" width="220"/>

</td>
</tr>
</table>

---

## 🤖 Agentic AI Workflow Architecture

Here's how I structure a Claude-powered agent that acts on real user data (like in NutriMate AI):

```mermaid
graph TD
    A[User Message] --> B(Claude Agent)
    B --> C{Tool Needed?}
    C -->|Yes| D[log_meal / log_water / log_weight]
    C -->|No| E[Direct Reply]
    D --> F[(SQLite via SQLAlchemy)]
    F --> G[Tool Result Returned to Claude]
    G --> H([Grounded Natural Language Reply])
    E --> H

    classDef default fill:#0d1117,stroke:#58A6FF,stroke-width:2px,color:#C9D1D9;
    classDef agent fill:#161b22,stroke:#bb9af3,stroke-width:2px,color:#C9D1D9;
    classDef tool fill:#161b22,stroke:#4ade80,stroke-width:2px,color:#C9D1D9;
    classDef output fill:#161b22,stroke:#f7768e,stroke-width:2px,color:#C9D1D9;

    class B agent;
    class D,F,G tool;
    class H output;
```

---

## 🛠️ Tech Stack

### 🔙 Backend Development
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white) ![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white) ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)

### 🎨 Frontend Development
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB) ![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

### 💻 Core Languages
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white) ![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white) ![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)

### 🤖 AI Toolkit — "What I Build With"
*"I don't just chat with these — I wire them into agents and full pipelines."*

![Claude](https://img.shields.io/badge/Claude-D97706?style=for-the-badge&logo=anthropic&logoColor=white) ![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white) ![TMDB API](https://img.shields.io/badge/TMDB_API-01D277?style=for-the-badge)

### 🚀 Tools & Version Control
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white) ![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)

---

## 🚀 Featured Projects

### 🎬 [CineBot — AI Movie Recommendation Chatbot](https://github.com/amoghvijay/Cinebot-movie-suggestion-ai)

<table>
<tr>
<td width="55%">

| Metric / Feature | Detail |
|---|---|
| 🧠 **AI-Powered** | 4 tailored movie picks via Google Gemini |
| 🖼️ **Rich Cards** | Live posters, ratings & overviews from TMDB |
| 💬 **Interface** | Guided quick-replies + free-text chat |
| 🔁 **Reliability** | Auto-retry logic for API hiccups |
| 🛠️ **Tech Stack** | Python, Flask, Gemini API, TMDB API |

</td>
<td width="45%">

[![CineBot Preview](https://raw.githubusercontent.com/amoghvijay/amoghvijay/main/cinebot-animation.svg)](https://github.com/amoghvijay/Cinebot-movie-suggestion-ai)

</td>
</tr>
</table>

### 🥗 [NutriMate AI — Personal Nutrition Agent](https://github.com/amoghvijay/Nutrimate-ai)

<table>
<tr>
<td width="55%">

| Metric / Feature | Detail |
|---|---|
| 🤖 **Action Agent** | Claude tool-calling logs meals from plain chat |
| 🧬 **Calculator** | BMI, BMR, TDEE & macros (Mifflin-St Jeor) |
| 📈 **Charts** | Live macro breakdown + weight trend |
| 🔐 **Auth** | Bcrypt-hashed passwords, session tokens |
| 🛠️ **Tech Stack** | FastAPI, SQLAlchemy, SQLite, Claude API |

</td>
<td width="45%">

[![NutriMate Preview](https://raw.githubusercontent.com/amoghvijay/amoghvijay/main/nutrimate-animation.svg)](https://github.com/amoghvijay/Nutrimate-ai)

</td>
</tr>
</table>

### 📄 [ResumeForge AI — Resume Analysis & Job Matching](https://github.com/amoghvijay/Resume-Forge-AI)

| Metric / Feature | Detail |
|---|---|
| 📤 **Parsing** | Extracts skills, experience & education from resumes |
| 🤖 **AI Agent** | Scores resume content against job listings |
| 🔍 **Job Fetching** | Pulls relevant listings for matching |
| 🛠️ **Tech Stack** | Python, FastAPI, SQLite |

### ☕ [Java Programs & Projects — Core Java Lab](https://github.com/amoghvijay/Java-Programs-and-Projects)

| Metric / Feature | Detail |
|---|---|
| 🧵 **Multithreading** | Thread, Runnable, sleep(), join(), sync |
| 📁 **File Handling** | Create, read, write, append, metadata |
| 🔤 **Strings** | String, StringBuffer, StringBuilder, palindrome |
| 🛠️ **Tech Stack** | Core Java |

---

## 📊 GitHub Statistics

<div align="center">

[![GitHub Trophies](https://github-profile-trophy.vercel.app/?username=amoghvijay&theme=tokyonight&no-bg=true&margin-w=15&no-border=true)](https://github.com/amoghvijay)

[![Amogh's GitHub Stats](https://github-readme-stats-fast.vercel.app/api?username=amoghvijay&show_icons=true&theme=tokyonight&hide_border=true)](https://github.com/amoghvijay) [![Top Languages](https://github-readme-stats-fast.vercel.app/api/top-langs/?username=amoghvijay&layout=compact&theme=tokyonight&hide_border=true)](https://github.com/amoghvijay)

[![Amogh's GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=amoghvijay&theme=tokyonight&hide_border=true)](https://github.com/amoghvijay)

[![Amogh's Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=amoghvijay&theme=tokyo-night&hide_border=true)](https://github.com/amoghvijay)

[![Snake Animation](https://raw.githubusercontent.com/amoghvijay/amoghvijay/output/github-contribution-grid-snake.svg)](https://github.com/amoghvijay)

</div>

---

## 🎯 Current Focus & Learning

```python
class CurrentFocus:
    building = [
        "AI Agents with Tool-Calling",
        "Full Stack AI-Powered Apps",
    ]
    learning = [
        "Machine Learning",
        "Deep Learning",
        "Generative AI",
    ]
    improving = [
        "Agentic Workflow Design",
        "Prompt Engineering",
        "System Design for AI Apps",
    ]
```

---

<div align="center">

*"If it's repetitive, automate it. If it's complex, agent-ify it."*
**— Amogh Vijay**

</div>
