<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=Sohan%20D'Souza&fontSize=60&fontColor=fff&animation=twinkling&fontAlignY=32&desc=AI%2FML%20Engineer%20%7C%20Full-Stack%20Developer%20%7C%20Fresher%202026&descAlignY=56&descSize=18" width="100%"/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=6BBBFF&center=true&vCenter=true&multiline=true&repeat=true&width=700&height=60&lines=Building+RAG+Pipelines+with+LangChain+%2B+LLaMA+3;Multi-Model+OCR+%7C+Computer+Vision+%7C+FastAPI;Full-Stack%3A+React+%2B+Django%2FFastAPI+%2B+PostgreSQL;Oracle+Certified+GenAI+%26+AI+Foundations" alt="Typing SVG" />
</a>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/sohan1919)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sohandsouza15@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Sohan-dsz)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://sohan19.netlify.app)

![Profile Views](https://komarev.com/ghpvc/?username=Sohan-dsz&color=6BBBFF&style=for-the-badge&label=PROFILE+VIEWS)

</div>

---

## 👋 About Me

```yaml
name: Sohan D'Souza
education: "B.E. Computer Science & Business Systems, SJEC Mangalore (VTU) — CGPA 8.94"
batch: "2026 (Fresher)"
location: "Shivamogga, Karnataka, India — open to relocation"
focus: ["AI/ML Engineering", "Computer Vision", "Full-Stack Development"]
currently: "Actively interviewing for AI/ML Engineer, SWE, and Full-Stack roles"
fun_fact: "Captained a 30-member team to AIR 3 nationally at BAJA SAE INDIA 2026"
```

---

## 🧠 How I Build AI Systems

A look at the kind of pipelines I actually ship — not just diagrams, these map to real projects below.

**HealthMate — Multimodal RAG Pipeline**

```mermaid
flowchart LR
    A["🎙️ Voice / 📷 Image / 💬 Text Query"] --> B["Whisper STT"]
    B --> C["BGE Embeddings"]
    C --> D[("ChromaDB\nVector Store")]
    D --> E["LLaMA 3\n(via Groq)"]
    E --> F["FastAPI Backend"]
    F --> G["⚛️ React Frontend"]
    style D fill:#6BBBFF,color:#000
    style E fill:#412991,color:#fff
```

**Document Analysis Studio — Production OCR Pipeline**

```mermaid
flowchart LR
    A["📄 Scanned Document"] --> B["OpenCV Preprocess"]
    B --> C["ORB + RANSAC\nHomography Align"]
    C --> D{"Multi-Model\nOCR Ensemble"}
    D --> E1["TrOCR"]
    D --> E2["DocTR"]
    D --> E3["EasyOCR"]
    E1 & E2 & E3 --> F["FastAPI + Celery/Redis\n(Async Jobs)"]
    F --> G["Prometheus / Grafana / Loki\nObservability"]
    style D fill:#6BBBFF,color:#000
    style F fill:#009688,color:#fff
```

---

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🎙️ HealthMate
Multimodal RAG-based AI health assistant. Voice and image input via **Whisper**, retrieval over **ChromaDB** with **BGE embeddings**, generation via **LLaMA 3 on Groq**, orchestrated with **LangChain**. Shipped with Docker + GitHub Actions CI/CD.

`LangChain` `ChromaDB` `Groq` `Whisper` `FastAPI` `Docker`

</td>
<td width="50%" valign="top">

### 🧾 Document Analysis Studio
Production-grade OCR system from my Geojit Technologies internship. **OpenCV** + **ORB/RANSAC** alignment feeding a **multi-model ensemble (TrOCR, DocTR, EasyOCR)**, served async via **Celery/Redis**, monitored with **Prometheus/Grafana/Loki**.

`OpenCV` `TrOCR` `DocTR` `EasyOCR` `Celery` `Grafana`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ☁️ NAAC Data Management Platform
Cloud-native accreditation data platform — **Django/React/PostgreSQL/Docker**, 🥇 1st prize at college project exhibition. Also rebuilt as an enterprise-grade **Java microservices** version with Spring Boot, Kafka, and Spring Cloud.

`Django` `React` `PostgreSQL` `Spring Boot` `Kafka`

</td>
<td width="50%" valign="top">

### 💬 EmoBhaava
Multilingual sentiment classifier built on **XLM-RoBERTa**, shipped with CI/CD and **Prometheus** metrics for live monitoring of model performance.

`XLM-RoBERTa` `Transformers` `Prometheus` `CI/CD`

</td>
</tr>
</table>

---

## 🛠️ Tech Stack

<div align="center">

**AI / ML**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-000000?style=flat-square&logo=chainlink&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-6BBBFF?style=flat-square)

**Backend & DevOps**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Oracle Cloud](https://img.shields.io/badge/Oracle%20Cloud-F80000?style=flat-square&logo=oracle&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

</div>

---

## 📊 GitHub Stats

<div align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=Sohan-dsz&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Sohan-dsz&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" />
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Sohan-dsz&theme=tokyonight&hide_border=true" />
</div>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Sohan-dsz&theme=tokyo-night&hide_border=true" width="100%"/>
</div>

---

## 🏆 Achievements & Certifications

```mermaid
timeline
    title Recent Milestones
    2026 : CGPA 8.94, B.E. CSBS — SJEC Mangalore
         : AIR 3 (ATVC), AIR 8 Overall — BAJA SAE INDIA
         : Geojit Technologies Internship (AIML + Full Stack)
         : Oracle Cloud — GenAI Professional & AI Foundations
         : Salesforce — Agentblazer Champion (Dev)
```

- 🥇 **AIR 3 (ATVC) & AIR 8 Overall** — BAJA SAE INDIA 2026, captaining a 30-member cross-functional team
- 🎓 **CGPA 8.94** — B.E. Computer Science & Business Systems, SJEC Mangalore
- 🏅 **Oracle Certified** — Cloud Infrastructure Generative AI Professional
- 🏅 **Oracle Certified** — AI Foundations Associate
- 🏅 **Salesforce Certified** — Agentforce, Apex, Flow · Agentblazer Champion (Dev)
- 🔬 **Production OCR System** — multi-model ensemble pipeline built during Geojit Technologies internship

---

## 🤝 Let's Connect

<div align="center">

I'm actively interviewing for **AI/ML Engineer**, **Software Engineer**, and **Full-Stack Developer** roles.
If you're working on something interesting — let's talk!

[![Email Me](https://img.shields.io/badge/📧%20Email%20Me-EA4335?style=for-the-badge)](mailto:sohandsouza15@gmail.com)
[![LinkedIn](https://img.shields.io/badge/Connect%20on%20LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/sohan1919)
[![Portfolio](https://img.shields.io/badge/View%20Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://sohan19.netlify.app)

</div>

---

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" width="100%"/>

*"Build systems that think. Ship products that matter."*

</div>
