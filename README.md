from pathlib import Path
import pypandoc

md = r"""# 👋 Hi, I'm Dharshini V T

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Poppins&size=28&pause=1000&color=38BDF8&center=true&vCenter=true&width=900&lines=Computer+Science+Engineering+Student;Frontend+Developer;Java+Developer;AI+%26+ML+Enthusiast;Full+Stack+Learner;Hackathon+Participant;Always+Learning+New+Technologies" />
</p>

<p align="center">
<img src="https://komarev.com/ghpvc/?username=Dharshini-8&label=Profile+Views&color=0e75b6&style=for-the-badge"/>
<img src="https://img.shields.io/github/followers/Dharshini-8?style=for-the-badge&logo=github"/>
<img src="https://img.shields.io/github/stars/Dharshini-8?style=for-the-badge"/>
</p>

---

# 💫 About Me

- 🎓 B.E. Computer Science Engineering Student
- 💻 Passionate about Frontend Development, AI & Machine Learning
- 🚀 Building real-world web applications and AI-powered projects
- 🌱 Currently learning Java, DSA, Full Stack Development, RAG, and LLMs
- 🏆 Hackathon Participant & Project Expo Winner

---

# 🛠️ Tech Stack

<p align="center">
<img src="https://skillicons.dev/icons?i=html,css,js,react,vite,tailwind,nodejs,express,java,c,python,mysql,mongodb,git,github,vscode,figma,postman,tensorflow" />
</p>

### 🌐 Frontend
HTML5 • CSS3 • JavaScript • React.js • Vite • Tailwind CSS

### ⚙️ Backend
Node.js • Express.js • REST APIs

### 💻 Languages
Java • JavaScript • C • Python (Basics)

### 🗄️ Databases
MySQL • MongoDB Atlas • ChromaDB

### 🤖 AI & ML
Artificial Intelligence • Machine Learning • Generative AI • Prompt Engineering • LLMs • LangChain • LangGraph • RAG • Ollama • AI Agents • Vector Databases • Embeddings

### ☁️ Deployment
Netlify • Vercel • Render

### 🛠️ Tools
Git • GitHub • VS Code • Google Colab • Postman • Figma • MongoDB Compass

---

# 🚀 Featured Projects

## 🔗 Zylink – Smart URL Analytics Platform
- URL Shortener with QR Codes
- Analytics Dashboard
- JWT Authentication
- Click Tracking
- React + Vite + Tailwind CSS + Node.js + Express.js + MongoDB Atlas

## 🩺 Mediscan – Smart Medicine Scanner
- QR/Barcode Scanner
- Medicine Information
- HTML • CSS • JavaScript

## 🐾 Pet Adoption Website
- Responsive Adoption Portal
- HTML • CSS • JavaScript

## 🎓 AI-Based Education Equity System
- AI Chatbot
- Assessment Module
- Teacher & Student Dashboard
- Progress Tracking

## 🚀 Placement Prep Tracker
- Coding Tracker
- Aptitude Tracker
- Interview Preparation
- Daily Goals
- Progress Dashboard

---

# 🏆 Achievements

- 🥇 Project Expo Winner
- 🏅 AIM'26 Hackathon Participant
- 🏅 NeuraHack 2.0 Participant
- 🏅 National Level Hackathon Participant
- 🏅 NPTEL Internet of Things (Elite)
- 🏅 NPTEL Cloud Computing

---

# 💻 Coding Profiles

<p align="center">
<a href="https://leetcode.com/u/Dharshini8/"><img src="https://img.shields.io/badge/LeetCode-Dharshini8-FFA116?style=for-the-badge&logo=leetcode&logoColor=black"/></a>
<a href="https://github.com/Dharshini-8"><img src="https://img.shields.io/badge/GitHub-Dharshini--8-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
<a href="https://www.linkedin.com/in/dharshini-v-t-54b675293"><img src="https://img.shields.io/badge/LinkedIn-Dharshini-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
</p>

## 💡 LeetCode Stats

<p align="center">
<img src="https://leetcard.jacoblin.cool/Dharshini8?theme=dark&font=Poppins&ext=contest"/>
</p>

---

# 🏆 GitHub Trophies

<p align="center">
<img src="https://github-profile-trophy.vercel.app/?username=Dharshini-8&theme=tokyonight&no-frame=true&row=2&column=4"/>
</p>

# 📊 GitHub Stats

<p align="center">
<img height="170" src="https://github-readme-stats.vercel.app/api?username=Dharshini-8&show_icons=true&theme=tokyonight"/>
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Dharshini-8&layout=compact&theme=tokyonight"/>
</p>

# 🔥 GitHub Streak

<p align="center">
<img src="https://github-readme-streak-stats.herokuapp.com?user=Dharshini-8&theme=tokyonight"/>
</p>

# 📈 Activity Graph

<p align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=Dharshini-8&theme=tokyo-night&hide_border=true"/>
</p>

# 📊 Contributor Stats

<p align="center">
<img src="https://github-contributor-stats.vercel.app/api?username=Dharshini-8&limit=5&theme=tokyonight&combine_all_yearly_contributions=true"/>
</p>

# 🎯 Current Focus

- AI & Machine Learning
- Java + DSA
- Full Stack Development
- Data Analytics
- Building Open Source Projects

# 💬 Quote

<p align="center">
<img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight"/>
</p>

# 📫 Connect

<p align="center">
<a href="mailto:vtdharshini8@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://www.linkedin.com/in/dharshini-v-t-54b675293"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="https://github.com/Dharshini-8"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
</p>

---

<p align="center">
⭐ <b>Learning continuously, building impactful projects, and growing one commit at a time.</b>
</p>
"""
out="/mnt/data/README.md"
Path(out).write_text(md,encoding="utf-8")
print(out)
