<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=220&section=header&text=Butla%20Vishnudev&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=CS%20Student%20%7C%20Full-Stack%20%2B%20ML%20Systems%20That%20Actually%20Run&descAlignY=58&descSize=17&stroke=7f5af0&strokeWidth=2" width="100%"/>

</div>

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com/?font=Fira+Code&size=19&duration=3000&pause=800&color=7F5AF0&center=true&vCenter=true&width=750&lines=A+two-process+job-matching+agent+that+emails+you+fits;A+civic+reporting+app+that+reads+the+photo+for+you;An+answer-grader+that+scores+on+meaning%2C+not+keywords;A+stock+tracker+with+its+own+5-day+forecast+model;A+medical+assistant+with+a+real+RAG+pipeline+underneath)](https://github.com/VishnudevButla)

</div>

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-vishnudev725-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vishnudev725/)
[![GitHub](https://img.shields.io/badge/GitHub-VishnudevButla-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/VishnudevButla)
[![Profile Views](https://komarev.com/ghpvc/?username=VishnudevButla&style=for-the-badge&color=7f5af0&label=PROFILE+VIEWS)](https://github.com/VishnudevButla)

</div>

---

## ✦ The short version

> I'm a third-year CS student who got tired of tutorials that end at "hello world" and started building things that had to work **end-to-end** — auth, a real database, background jobs, an actual UI on top. Every project below runs live, and every description here is pulled straight from that project's own README, not written up after the fact to sound impressive.

---

## 🚀 What I've actually shipped

<details open>
<summary><b>🗺️ TalentMap — Job-matching agent that runs end-to-end</b></summary>

<br>

> A resume-to-job matching agent, not a form. It runs as **two processes that only talk through MongoDB** — a FastAPI app and a separate APScheduler worker — so a redeploy of the API never kills an in-progress job scan. Resumes get parsed by **Llama 3.3 70B on Groq**, jobs get pulled from Adzuna + RemoteOK, and both sides are matched with **BGE embeddings + weighted cosine similarity** across skills, experience, education, and certifications — then the best fits land in your inbox.

[![Repo](https://img.shields.io/badge/View%20Repo-TalentMap-7f5af0?style=flat-square&logo=github)](https://github.com/VishnudevButla/TalentMap)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Groq](https://img.shields.io/badge/Groq%20Llama%203.3-FF6B35?style=flat-square)
![AWS S3](https://img.shields.io/badge/AWS%20S3-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)
![APScheduler](https://img.shields.io/badge/APScheduler-4B8BBE?style=flat-square&logo=python&logoColor=white)

</details>

---

<details open>
<summary><b>🛠️ Fixora — Civic reporting that reads the photo for you</b></summary>

<br>

> Built for the **Google × Coding Ninjas Vibe2Ship hackathon**. Report a pothole, a leak, a broken streetlight with one photo — **Gemini AI reads the image** and fills in the category, severity, and description itself. Issues get geo-tagged onto a live community map, nearby users can verify instead of duplicating reports, and there's a **points-based leaderboard** to keep people actually reporting.

[![Repo](https://img.shields.io/badge/View%20Repo-Fixora-7f5af0?style=flat-square&logo=github)](https://github.com/VishnudevButla/Fixora)
![React](https://img.shields.io/badge/React+Vite-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![Gemini](https://img.shields.io/badge/Google%20Gemini-4285F4?style=flat-square&logo=google&logoColor=white)
![Leaflet](https://img.shields.io/badge/React%20Leaflet-199900?style=flat-square&logo=leaflet&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

</details>

---

<details open>
<summary><b>📝 AutoGrade — Scores meaning, not keyword overlap</b></summary>

<br>

> Descriptive-answer grading that scores meaning, not keyword overlap. Professors upload model answers, students submit theirs — both get embedded with **all-MiniLM-L6-v2 sentence transformers**, and scores come from a **cosine-similarity search against Pinecone**, with everything else stored in TiDB behind a FastAPI backend.

[![Repo](https://img.shields.io/badge/View%20Repo-AutoGrade-7f5af0?style=flat-square&logo=github)](https://github.com/VishnudevButla/AutoGrade)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![SentenceTransformers](https://img.shields.io/badge/Sentence%20Transformers-FF9A3C?style=flat-square)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=flat-square)
![TiDB](https://img.shields.io/badge/TiDB-CC0200?style=flat-square)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square)

</details>

---

<details open>
<summary><b>📈 QuantIQ — A stock tracker that also predicts</b></summary>

<br>

> Live quotes, top movers, and news sentiment come from **Alpha Vantage** and get cached in Postgres (Neon) so the app isn't hammering the API on every page load — and a **scikit-learn Linear Regression model** layered on SMA-10/SMA-30 produces a **5-business-day price forecast** for anything on your watchlist.

[![Repo](https://img.shields.io/badge/View%20Repo-QuantIQ-7f5af0?style=flat-square&logo=github)](https://github.com/VishnudevButla/QuantIQ)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL%20Neon-336791?style=flat-square&logo=postgresql&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=flat-square&logo=chartdotjs&logoColor=white)

</details>

---

<details open>
<summary><b>🩺 MedPal — A full-stack health assistant with a real RAG pipeline</b></summary>

<br>

> Not a symptom-checker gimmick. It runs **four ML models** (scikit-learn + XGBoost) for diabetes, heart, kidney, and lung-cancer risk assessment; a **Gemini-2.0-Flash chatbot** via LangChain for conversational medical Q&A; and a proper **RAG pipeline** — upload an X-ray or a medical PDF, and it's chunked, embedded with HuggingFace sentence-transformers, stored in Pinecone, and made queryable. Deployed live on Render.

[![Repo](https://img.shields.io/badge/View%20Repo-MedPal-7f5af0?style=flat-square&logo=github)](https://github.com/VishnudevButla/MedPal)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini%202.0%20Flash-4285F4?style=flat-square&logo=google&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square)
![XGBoost](https://img.shields.io/badge/XGBoost-EA4335?style=flat-square)
![Pinecone](https://img.shields.io/badge/Pinecone%20RAG-000000?style=flat-square)
![Render](https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=black)

</details>

---

## 🧰 What's actually in the toolbox

<div align="center">

[![My Skills](https://skillicons.dev/icons?i=py,js,ts,react,fastapi,flask,mongodb,postgres,firebase,git,github,vite,tailwind,html,css&perline=8)](https://github.com/VishnudevButla)

</div>

---

## 📊 The numbers, for what they're worth

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=VishnudevButla&show_icons=true&theme=midnight-purple&hide_border=true&count_private=true&include_all_commits=true&bg_color=0f0c29&title_color=7f5af0&icon_color=7f5af0&text_color=fffffe&ring_color=7f5af0" width="49%"/>
<img src="https://streak-stats.demolab.com?user=VishnudevButla&theme=midnight-purple&hide_border=true&background=0f0c29&stroke=7f5af0&ring=7f5af0&fire=ff7b72&currStreakNum=fffffe&sideNums=fffffe&currStreakLabel=7f5af0&sideLabels=94a1b2&dates=94a1b2" width="49%"/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=VishnudevButla&layout=compact&theme=midnight-purple&hide_border=true&langs_count=8&bg_color=0f0c29&title_color=7f5af0&text_color=fffffe" width="49%"/>

</div>

---

## 🌿 Contribution Graph

<div align="center">

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=VishnudevButla&theme=tokyo-night&bg_color=0f0c29&color=7f5af0&line=7f5af0&point=2cb67d&area=true&area_color=302b63&hide_border=true&custom_title=Contribution%20Activity)](https://github.com/VishnudevButla)

</div>

---

## 🐍 Where the commits go

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/VishnudevButla/VishnudevButla/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/VishnudevButla/VishnudevButla/output/github-contribution-grid-snake.svg">
  <img alt="GitHub Contribution Snake" src="https://raw.githubusercontent.com/VishnudevButla/VishnudevButla/output/github-contribution-grid-snake-dark.svg" width="100%">
</picture>

<sub>↳ Snake updates daily via GitHub Actions — see setup note below if not showing yet</sub>

</div>

---

## 📬 Reach me

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vishnudev725/)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/VishnudevButla)
[![Email](https://img.shields.io/badge/Email-Say%20Hi-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:vishnudevbutla@gmail.com)

</div>

---

<div align="center">

<sub>If a repo down here looks half-finished, it's probably still teaching me something. That's the deal.</sub>

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=120&section=footer" width="100%"/>
