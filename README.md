<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=26&pause=1200&color=4F46E5&center=true&vCenter=true&width=900&lines=Hi+I'm+Ajit+Babu+Kakumanu+👋;Creator+of+Modern+Resume+Analyzer;AI+%7C+Data+Science+%7C+App+Developer;Let’s+build+something+awesome+🚀" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/kakumanu-ajit-babu-804951334/">
    <img src="https://img.shields.io/badge/LinkedIn-Ajit%20Babu%20Kakumanu-blue?style=for-the-badge&logo=linkedin" />
  </a>
  <a href="https://github.com/nani26-begin">
    <img src="https://img.shields.io/badge/GitHub-nani26--begin-black?style=for-the-badge&logo=github" />
  </a>
</p>

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=nani26-begin&theme=tokyonight&no-frame=true&row=1&column=7" />
</p>

---

## 🚀 Modern Resume Analyzer

An AI-powered web application that analyzes resumes like an **ATS + Recruiter + Job Market**.

It provides:
✔ Resume section scoring  
✔ Skills match for selected job role  
✔ Experience-based salary prediction  
✔ Smart improvement suggestions  
✔ Fully interactive and animated UI  

---

## ✨ Live Preview (GIF / Demo)

<p align="center">
  <img src="https://user-images.githubusercontent.com/74038190/212284181-57f8c7c0-48b5-4d3b-a5d3-1e1e70e98b7e.gif" width="700"/>
</p>

---

## 🧠 Features

🔹 ATS-style resume evaluation  
🔹 Role-based skills analysis  
🔹 Salary estimation based on:
  - Role  
  - Company tier  
  - Experience  
🔹 Visual results using Radar + Speedometer charts  
🔹 Modern UI with animations  
🔹 Supports PDF / DOCX / TXT resumes  

---

## 🖥️ Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,html,js,react,flask,github,git,vscode" />
</p>

- Python  
- Gradio  
- spaCy & NLTK (NLP)  
- Plotly (Charts)  
- PyPDF2 & python-docx  

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=nani26-begin&show_icons=true&theme=tokyonight&border_radius=15" width="48%" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=nani26-begin&theme=tokyonight&border_radius=15" width="48%" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=nani26-begin&layout=compact&theme=tokyonight&border_radius=15" />
</p>

---

## 🐍 Contribution Snake Animation

<p align="center">
  <img src="https://raw.githubusercontent.com/nani26-begin/nani26-begin/output/github-contribution-grid-snake.svg" />
</p>

---

## ⚙ How to Run

```bash
git clone https://github.com/nani26-begin/modern-resume-analyzer.git
cd modern-resume-analyzer
pip install -r requirements.txt
python app.py
For Colab:

python
Copy code
demo.launch(share=True)
🌍 Connect With Me
<p align="center"> <a href="https://www.linkedin.com/in/kakumanu-ajit-babu-804951334/"> <img src="https://img.shields.io/badge/LinkedIn-Ajit%20Babu%20Kakumanu-blue?style=for-the-badge&logo=linkedin" /> </a> <a href="https://github.com/nani26-begin"> <img src="https://img.shields.io/badge/GitHub-nani26--begin-black?style=for-the-badge&logo=github" /> </a> </p>
<p align="center"> <img src="https://capsule-render.vercel.app/api?type=waving&color=4F46E5&height=120&section=footer"/> </p> ```
🔥 Bonus: Contribution Snake Setup
To make the snake animation work, create this GitHub Action file:

📁 .github/workflows/snake.yml

yaml
Copy code
name: Generate Snake

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: nani26-begin
          outputs: dist/github-contribution-grid-snake.svg
      - uses: crazy-max/ghaction-github-pages@v3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
