<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=150&section=header&text=Abdeljalil%20Otman&fontSize=40" alt="banner"/>
</p>

# Hi — I'm **Abdeljalil Otman** 👋  
**Aspiring AI / ML Engineer & Researcher** | building intelligent systems that solve real problems

<p align="center">
  <!-- Replace placeholders with your links -->
  <a href="<your-portfolio-link>" target="_blank"><img src="https://img.shields.io/badge/Portfolio-View-blue?style=for-the-badge&logo=google-chrome" alt="portfolio"/></a>
  <a href="mailto:Abdeljalil.Otman@um6p.ma"><img src="https://img.shields.io/badge/Email-Abdeljalil.Otman@um6p.ma-important?style=for-the-badge&logo=gmail" alt="email"/></a>
  <a href="https://www.linkedin.com/in/abdeljalil-otman-2825a51a5/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin" alt="linkedin"/></a>
</p>

---

## 🚀 Quick snapshot
- 🔭 Currently: **working on an implementation of self adapting language models proposed by some researchers at MIT.**  
- 🌱 Learning: **fine tuning and LLM functionalities**  
- 🧩 Strengths: Python, TensorFlow/PyTorch, feature engineering, model deployment, data engineering, Go/Java backend integration  
- 🎯 Looking for: internship / research roles in **AI / ML / Data Science**

---

## 🛠 Tech Stack (most used)
<p>
  <img src="https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" /> 
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" />
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" />
  <img src="https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white" />
  <img src="https://img.shields.io/badge/SpringBoot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" />
  <img src="https://img.shields.io/badge/React-35495E?style=for-the-badge&logo=react&logoColor=4FC08D" />
  <img src="https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vue.js&logoColor=4FC08D" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
</p>

---

## 📂 Featured Projects
> Click the repo links in your pinned list for full code, README, demos.

## 🧠 **Mini Self-Adapting Language Model (SEAL-Inspired) for Low-End Hardware**

**What:**
An end-to-end **self-adapting language model** pipeline inspired by the SEAL (Self-Adapting Language Models) paper — implemented to run efficiently on **low-end hardware**.

**Highlights:**

* 🔄 **Full adaptive learning loop**:

  1. Baseline model evaluation (Exact Match / F1)
  2. Teacher-generated self-edits (DeepSeek via OpenRouter API)
  3. LoRA fine-tuning on synthetic examples
  4. Automatic ΔF1 analysis to keep best self-edits
* 💡 **Student–Teacher approach:** The smaller model continuously refines itself using feedback from the stronger model.
* ⚙️ **Lightweight fine-tuning:** LoRA configuration optimized for CPU training (rank = 8, lr = 2e-5).
* 📊 **Evaluation metrics:** Exact Match / F1 score improvement (+0.04 → +0.27 F1).
* 🧩 **Data pipeline:** Q/A dataset generation → synthetic edits → filtered self-edits → fine-tuning.
* ☁️ **Deployment-ready:** Model inference exposed via a simple **Flask REST API**, containerized with **Docker** for reproducibility.

**Model:**
`openai-community/gpt2` + LoRA adapters (Fine-tuned with SEAL-style self-edits)
**Performance:**
F1 ≈ **0.27** (↑ from 0.04) | Exact Match ≈ **0.15**

### 🐍 Tech Stack
- `Transformers`, `PEFT`, `Datasets`, `Torch`
- `LoRA` for efficient fine-tuning
  
---
### 🤖 <Project B — short name>  
**What:** `<one-line>` — e.g., "Time-series prediction for environmental sensors"  
**Highlights:**  
- Feature engineering for sensor drift & missing data  
- Model explainability: SHAP plots included  
- Notebook + reproducible scripts (see `/notebooks` and `/src`)  
**Live demo / API:** `<link-if-deployed>`

---

### 🧠 <Project C — short name>  
**What:** `<one-line>` — e.g., "Chatbot / NLP project with Arabic language support"  
**Highlights:**  
- Custom tokenizer and dataset preprocessing  
- Fine-tuned transformer, evaluation & error analysis included  
- CI: GitHub Actions for unit tests and linting

---

## 🧭 How I Work — typical pipeline
1. ✅ Problem definition & metric selection  
2. 📊 Data cleaning, EDA, and feature engineering  
3. ⚙️ Model selection, training, hyperparameter tuning  
4. 🔍 Evaluation, error analysis & interpretability (SHAP/LIME)  
5. 🚀 Packaging & deployment (API / edge / container)  
6. ♻️ Monitoring & iteration

---

## 📈 GitHub Activity & Stats
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=AbdeljalilOtman&theme=blueberry&show_icons=true&count_private=true" alt="github-stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=AbdeljalilOtman&layout=compact&theme=blueberry" alt="top-langs" />
</p>

---

## 📚 Selected artifacts / deliverables
- Papers / Reports: **<link or leave empty>**  
- Kaggle / Competitions: **<link or leave empty>**  
- Datasets I collected: **<link or leave empty>**

---

## 🤝 Open to
- Internship / research opportunities in **AI / ML / Data Science**  
- Mentorship & collaborations on applied ML projects  
- Short freelance projects: model prototyping, data pipelines, deployment

---

## 📫 Contact
- **Email:** Abdeljalil.Otman@um6p.ma  
- **LinkedIn:** <your-linkedin-url>  
- **Portfolio:** <your-portfolio-url>  

---

<p align="center">  
  <sub>Built with ❤️ — updates frequently. Tip: add animated GIFs for your demos (put them in `/assets` and reference them above).</sub>
</p>
