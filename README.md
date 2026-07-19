<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:5B21B6,100:7C3AED&height=180&section=header" width="100%"/>

<br/>

# Dheeksha N

<a href="#ai--ml-expertise"><img src="https://img.shields.io/badge/AI%2FML%20Engineering-1e2327?style=for-the-badge" /></a>
<a href="https://bmsit.ac.in/"><img src="https://img.shields.io/badge/BMSIT,%20Bengaluru-1e2327?style=for-the-badge" /></a><a href="https://www.google.com/maps/place/Karnataka,+India"><img src="https://img.shields.io/badge/Karnataka,%20India-7C3AED?style=for-the-badge" /></a>
<a href="#achievements"><img src="https://img.shields.io/badge/CGPA-9.2-1e2327?style=for-the-badge" /></a>

<br/><br/>

<a href="https://www.linkedin.com/in/dheekshanaveen/"><img src="https://img.shields.io/badge/LINKEDIN-7C3AED?style=for-the-badge" /></a>
<a href="mailto:dheekshanaveen12@gmail.com"><img src="https://img.shields.io/badge/EMAIL-1e2327?style=for-the-badge" /></a>
<a href="https://github.com/dheekshanaveen"><img src="https://img.shields.io/badge/GITHUB-7C3AED?style=for-the-badge" /></a>

<br/><br/>

![Profile Views](https://komarev.com/ghpvc/?username=dheekshanaveen&color=1e2327&style=for-the-badge&label=PROFILE+VIEWS)
<img src="https://img.shields.io/github/followers/dheekshanaveen?style=for-the-badge&label=FOLLOWERS&color=1e2327" />

</div>

---

## About

AI/ML Engineering undergraduate at BMS Institute of Technology & Management, Bengaluru, working across large language models, retrieval-augmented generation, and computer vision.

My work spans a real-time computer-vision fitness tracker, a retrieval-augmented academic chatbot, and an agentic AI system for lending workflows — with a consistent focus on shipping things that run end to end, not prototypes that only work in a demo.

I'm also active in Coding Club, BMSIT, where I've held Core Member, Marketing Associate, and Vice President roles.

**Open to:** ML/AI internships · backend engineering roles · research collaborations · open-source contributions.

---

## Tech Stack

<div align="center">
<img src="https://skillicons.dev/icons?i=python,flask,opencv,c,cpp,html,css,js,git,github,vscode,linux" />
</div>

---

## AI / ML Expertise

| Domain | Proficiency | Details |
|---|---|---|
| Computer Vision | ▰▰▰▰▰▰▰▱▱▱ Proficient | MediaPipe pose estimation, OpenCV, real-time landmark tracking |
| LLM & RAG | ▰▰▰▰▰▰▰▱▱▱ Proficient | LangChain, retrieval-augmented generation, prompt engineering |
| Agentic AI Systems | ▰▰▰▰▰▱▱▱▱▱ Intermediate | Multi-agent workflow design in Python |
| Backend Engineering | ▰▰▰▰▰▰▰▱▱▱ Proficient | Flask, REST APIs, Python |
| Applied Hackathon Engineering | ▰▰▰▰▰▱▱▱▱▱ Intermediate | Smart India Hackathon — environmental-tech MRV system |

---

## Featured Projects

<details>
<summary><b>Fitphile — AI Fitness Tracker with Pose Detection</b></summary>
<br/>
Flask application using OpenCV and MediaPipe Pose to track and count exercise reps (push-ups, squats, lunges, planks) in real time, with voice feedback at rep milestones.
<br/><br/>
<code>Python</code> <code>Flask</code> <code>OpenCV</code> <code>MediaPipe</code>
<br/><br/>
<a href="https://github.com/dheekshanaveen/fitphile-">View Repository →</a>
</details>

<details>
<summary><b>Academic RAG Chatbot — LLM Knowledge Assistant</b></summary>
<br/>
LLM-based chatbot using retrieval-augmented generation to answer academic questions grounded in institutional documents rather than model memory alone. Actively in development.
<br/><br/>
<code>Python</code> <code>LangChain</code> <code>RAG</code>
<br/><br/>
<a href="https://github.com/dheekshanaveen/LLM-based-academic-chabot-with-RAG">View Repository →</a>
</details>

<details>
<summary><b>Agentic Lending System — Multi-Agent Workflow</b></summary>
<br/>
Python-based agentic AI system automating stages of a loan lending workflow through cooperating AI agents.
<br/><br/>
<code>Python</code> <code>Agentic AI</code>
<br/><br/>
<a href="https://github.com/dheekshanaveen/agentic_lending_system">View Repository →</a>
</details>

<details>
<summary><b>Blue Carbon MRV — Smart India Hackathon</b></summary>
<br/>
Environmental-tech monitoring, reporting, and verification system for blue carbon tracking, built for Smart India Hackathon.
<br/><br/>
<code>Environmental Tech</code> <code>Hackathon</code>
</details>

---

## Experience

**Core Member · Marketing Associate · Vice President** — [Coding Club, BMSIT](https://bmsit.ac.in/)
`2024 – Present`

Contributed across club operations and technical event organizing in roles of increasing responsibility.

---

## GitHub Analytics

<div align="center">
<img height="160" src="https://github-readme-stats.vercel.app/api?username=dheekshanaveen&show_icons=true&theme=dark&hide_border=true&title_color=7C3AED" />
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=dheekshanaveen&layout=compact&theme=dark&hide_border=true&title_color=7C3AED" />
<br/>
<img src="https://github-readme-streak-stats.herokuapp.com/?user=dheekshanaveen&theme=dark&hide_border=true&ring=7C3AED&fire=7C3AED" />
</div>

## Trophies

<div align="center">
<img src="https://github-profile-trophy.vercel.app/?username=dheekshanaveen&theme=dark&no-frame=true&no-bg=true&column=7&margin-w=8" />
</div>

## Contribution Activity

<div align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=dheekshanaveen&theme=react-dark&hide_border=true&color=7C3AED&line=7C3AED" width="100%"/>
</div>

name: Generate Snake

on:
  schedule:
    - cron: "0 0 * * *"  # runs once a day
  workflow_dispatch: {}
  push:
    branches:
      - main

jobs:
  generate:
    permissions:
      contents: write
    runs-on: ubuntu-latest
    steps:
      - name: Generate snake game SVG
        uses: Platane/snk@v3
        with:
          github_user_name: dheekshanaveen
          outputs: |
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark
            dist/github-contribution-grid-snake.svg

      - name: Push output to output branch
        uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

## Current Focus

```text
learning:
  - Retrieval-augmented generation architectures and evaluation
  - Agentic multi-model LLM pipelines
  - Computer vision and pose-estimation techniques

building:
  - Academic RAG chatbot for institutional knowledge retrieval
  - Agentic lending workflow automation
  - Extending Fitphile with additional exercise recognition

open_to:
  - ML / AI engineering internships
  - Backend and systems engineering roles
  - Research collaborations
  - Open-source contributions
```

---

## Achievements

| Recognition | Details |
|---|---|
| CGPA 9.2 | AI/ML Engineering, BMSIT |
| Smart India Hackathon | Blue Carbon MRV — environmental-tech MRV system |
| Web Development Certification | Udemy |
| Python & SQL Certification | Udemy |
| Full Stack Web Development| Completed |
| Coding Club, BMSIT | Core Member · Marketing Associate · Vice President |

---

## Connect

<div align="center">

<a href="mailto:dheekshanaveen12@gmail.com"><img src="https://img.shields.io/badge/GMAIL-1e2327?style=for-the-badge&logo=gmail&logoColor=white" /><img src="https://img.shields.io/badge/DHEEKSHANAVEEN12%40GMAIL.COM-7C3AED?style=for-the-badge" /></a>

<br/><br/>

<a href="https://www.linkedin.com/in/dheekshanaveen/"><img src="https://img.shields.io/badge/LINKEDIN-1e2327?style=for-the-badge" /><img src="https://img.shields.io/badge/DHEEKSHANAVEEN-7C3AED?style=for-the-badge" /></a>

<br/><br/>

<a href="https://github.com/dheekshanaveen"><img src="https://img.shields.io/badge/GITHUB-1e2327?style=for-the-badge&logo=github&logoColor=white" /><img src="https://img.shields.io/badge/DHEEKSHANAVEEN-7C3AED?style=for-the-badge" /></a>

</div>

---

<div align="center">
<i>Build things that work end to end — not things that only work in a demo.</i>

<br/><br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:7C3AED,100:5B21B6&height=100&section=footer" width="100%"/>
</div>
