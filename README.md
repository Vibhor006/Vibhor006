<h1 align="center">✨ AI Tool Starter — by Vibhor Rastogi ✨</h1>

<p align="center">
  <img src="https://media.giphy.com/media/L8K62iTDkzGX6/giphy.gif" width="250" alt="AI Animation"/>
</p>

<p align="center">
  <a href="https://linkedin.com/in/vibhor-rastogi-5628aa280">
    <img src="https://img.shields.io/badge/-LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="https://github.com/Vibhor006">
    <img src="https://img.shields.io/badge/-GitHub-black?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
</p>

---

## 👨‍💻 About Me

- 🎓 B.Tech CSE Student @ KIET (2023 - 2027)  
- 🤖 Passionate about Web Development, Machine Learning & AI  
- 🌍 Open Source | 🏏 Cricket | 🎶 Music Production  

---

## 🛠 Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=java,cpp,c,python,html,css,js,react,next,nodejs,express,mongodb,firebase" /><br/>
  <img src="https://skillicons.dev/icons?i=git,github" />
</p>

---

## 🚀 Projects

- **AI-Powered Video Call App** – Real-time calling + AI agents (React.js, Next.js, WebRTC, AI APIs)  
- **NotesStack Web App** – MERN notes app with JWT auth & dark mode  
- **Depression Detection Model** – ML classifier on survey responses (Decision Tree)  
- **To-Do List Web App** – Firebase auth + responsive UI  

---

## 🎓 Certifications

- IBM Cloud Computing Fundamentals  
- MongoDB and Document Model  
- Microsoft Azure Security Technologies  
- Web Developer Bootcamp (Colt Steele, Angela Yu, Maximilian)  
- ML & AI A-Z (Udemy)  

---

## ⚡ Interests

💡 Open Source | 💻 Web Development | 🤖 Machine Learning | 🏏 Cricket | 🎶 Music  

---

<details>
<summary>⭐ Fun Animation</summary>
<p align="center">
  <img src="https://media.giphy.com/media/3o7aD6hIqhP7ObVzbG/giphy.gif" alt="coding" width="400"/>
</p>
</details>

---

# 🧠 AI Tool Starter (ML + Generative AI)

This repo is a **production-ready starter** for building Machine Learning & Generative AI tools.

### ✨ Features
- 🧱 Clean Python package layout (`src/`)  
- ⚡ Typer CLI (`train`, `generate`, `serve`)  
- 🌐 FastAPI API endpoints (`/generate`, `/classify`)  
- 🧪 PyTest + GitHub Actions CI  
- 📦 Docker support  
- 🧹 Pre-commit hooks  

---

## ⚙️ Quickstart

```bash
# Create & activate environment
python -m venv .venv && source .venv/bin/activate

# Install
pip install -e .[dev]

# Run tests
pytest -q

# Train the classifier
aitool train --model logistic --dataset iris

# Generate text with GPT-2
aitool generate --prompt "Once upon a time" --max-new-tokens 40

# Start API server
aitool serve --host 0.0.0.0 --port 8000
