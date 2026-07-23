---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

# Sam Shelly

**Computer Science & Astronomy | Vassar College**
Weed, CA, USA · [samgshelly@gmail.com](mailto:samgshelly@gmail.com) · [linkedin.com/in/sam-g-shelly](https://linkedin.com/in/sam-g-shelly/) · [github.com/SamZombie](https://github.com/SamZombie) · [samzombie.github.io](https://samzombie.github.io)

---

## Resumes

I keep three versions of my resume, tailored to different audiences. Pick the one that fits, or expand the sections below for the full history.

| Version | Best for | |
|---|---|---|
| **Full History** | A complete record — every role, project, publication, and activity | [Download PDF](https://samzombie.github.io/portfolio/Sam-Shelly-Resume-Full.pdf) |
| **Research** | Graduate programs, research assistantships, astrophysics/ML research roles | [Download PDF](https://samzombie.github.io/portfolio/Sam-Shelly-Resume-Research.pdf) |
| **Software Engineering** | AI/software engineering roles | [Download PDF](https://samzombie.github.io/portfolio/Sam-Shelly-Resume-SWE.pdf) |

---

## Full History

*Click a section to expand it. The content mirrors the Full History PDF above.*

<details markdown="1">
<summary><strong>Education</strong></summary>

**Vassar College** — Poughkeepsie, NY
Bachelor of Arts in Computer Science, Minor in Astronomy
*Aug 2022 – May 2026* | GPA: 3.64/4.00 | Major GPA: 3.68/4.00

Relevant Coursework: Data Structures & Algorithms, Analysis of Algorithms, Software Design, Compilers, Theory of Computation, Computer Organization, Natural Language Processing, Numerical Methods, Autonomous Robotics Design

**Danish Institute for Study Abroad** — Copenhagen, Denmark
*Jan 2025 – May 2025*
Junior Spring Semester Abroad

Relevant Coursework: Game Development, Ethics of Artificial Intelligence

</details>

<details markdown="1">
<summary><strong>Experience</strong></summary>

**AI Development Intern** — Innovative Computing Systems, Los Angeles, CA
*May 2025 – Jan 2026*

- Led a four person team to architect a Microsoft Copilot Studio knowledge agent for a 60-person systems integration firm.
- Restricted the agent to closed, company-fed data sources to protect client IP and eliminate public internet exposure.
- Built Python ingestion pipelines and ConnectWise API integrations to power AI-driven enterprise search, reducing information retrieval time by 30%.
- Launched a 15-user pilot and led technical evaluations for clients, advancing the product towards commercialization.

**Undergraduate Research Assistant** — Vassar College, Poughkeepsie, NY
*Jun 2024 – Sep 2024*

- Analyzed MAIHEM/FLASH magnetohydrodynamic simulations of a Milky Way-type galaxy's circumgalactic medium at different metallicities.
- Built visualizations like radial Mach-Alfvén profiles, angular momentum phase plots, and magnetic/kinetic energy density evolution to investigate turbulence-driven magnetic field evolution.
- Discovered that turbulent feedback drives disk instability and outward propagation of cold, magnetized gas that saturates the CGM's magnetic field.
- Co-authored research paper which was presented at the KNAC Undergraduate Symposium 2024.

**Computer Science Dept. Coach** — Vassar College, Poughkeepsie, NY
*Jan 2024 – May 2026*

- Led three sessions per week on algorithms, data structures, and debugging in Java for up to 50 students per semester (200+ total), adapting pacing and session plans for struggling students.
- Mentored two coaches, and met weekly with the course professor to align on curriculum direction and student learning progress.

</details>

<details markdown="1">
<summary><strong>Publications</strong></summary>

### Conference Papers

**Feedback-Driven Magnetic Field Evolution in MW-type Simulated Circumgalactic Medium**
Param P. Gogia, Umman Azan, **Sam Shelly**, Edward Buie II
*KNAC Undergraduate Symposium Proceedings*, 2024

- Investigated turbulence-driven feedback's role in magnetic field evolution in the CGM of a simulated Milky Way-type galaxy across three MAIHEM MHD simulations (two solar-metallicity, one at 0.3 Z☉).
- Found that feedback induces late-stage magnetic field saturation via disk instability and outward propagation of cold, magnetized gas, versus steady cubic growth in the no-feedback case.
- Analyzed post-simulation Mach-Alfvén profiles, angular momentum phase plots, magnetic/kinetic energy density evolution, and built data visualizations.

[[Paper]](http://samzombie.github.io/publications/paper1-URSI-2024.pdf) · [[Slides]](http://samzombie.github.io/publications/slides1-URSI-2024.pdf)

### Class Projects

**Efficacy of NER Models on Fiction and Nonfiction Domains**
Duncan Beauchamp, **Sam Shelly**
*CMPU 366 Natural Language Processing, Vassar College*, 2025

- Evaluated cross-domain performance of a DistilBERT-based NER model on literary fiction (LitBank) vs. expository text (OntoNotes), restricted to shared PER/LOC/ORG entity types.
- Reduced F1 domain gap between genres from 0.368 to 0.128 by fine-tuning on a mixed-domain corpus, raising LitBank micro-F1 from 0.26 to 0.72.
- Built the training data pipeline, involving dataset loading, chunking, oversampling, and train/validation/test splits.

[[Paper]](http://samzombie.github.io/publications/paper2-NLP-2025.pdf) · [[Slides]](http://samzombie.github.io/publications/slides2-NLP-2025.pdf) · [[Code]](https://github.com/d-beauchamp/ner-genre-evaluation)

</details>

<details markdown="1">
<summary><strong>Projects</strong></summary>

**AI Knowledge Base RAG** · [GitHub](https://github.com/SamZombie/AI-Knowledge-Base-RAG)
*Python, FastAPI, LangChain, Qdrant, Ollama, Mistral 7B, BAAI/bge-large-en-v1.5, PyMuPDF, Docker, Streamlit, pytest, GitHub Actions*

- Built a closed-loop Retrieval-Augmented Generation (RAG) system using self-hosted, open-weight components with no external API calls to securely query government and defense AI policy documents in air-gapped and other privacy-sensitive environments.
- Developed a custom LLM-as-judge evaluation pipeline achieving 0.95 retrieval recall and 0.92 answer similarity across a ground-truth QA dataset, with results visualized in a Streamlit dashboard.
- Built an end-to-end document ingestion and retrieval pipeline using PyMuPDF, semantic chunking, BAAI/bge-large-en-v1.5 embeddings, Qdrant vector search, and Mistral 7B (Ollama) for grounded, cited responses.
- Deployed the application as a Dockerized FastAPI REST service with automated testing and CI/CD using GitHub Actions.

**DataFest 2024 — Best Overall Analysis**
*Python, pandas | 48-hour competition*

Analyzed student-interaction data (video views, quiz attempts, textbook page views; n≈1,857 students) from an online statistics textbook to advise an ed-tech client on improving learning outcomes.

- Built a multiple regression model (R²=0.47) identifying quiz effort and video engagement as positive predictors of student performance, and quantified that textbook-only engagement and frequent answer-changing predicted lower scores.
- Built a pandas-based directed dependency graph mapping how students navigated between textbook chapters/sections while studying, informing a recommendation to prepend review material to high-traffic "capstone" chapters.
- Authored final write-up and slide presentation synthesizing both analyses into client-facing recommendations.

**PPO Driving Algorithm** · [GitHub](https://github.com/SamZombie/Driving-AI)
*Python, stable_baselines3, matplotlib, gymnasium, numpy, pygame*

- Trained a 2D autonomous driving agent via Proximal Policy Optimization to navigate a gated course, achieving a 100% gate-pass rate with an asymptotic S-curve reward convergence over ~16M timesteps.
- Demonstrated policy generalization by extrapolating the trained agent to unseen course layouts, achieving a 75% gate-pass rate on unseen courses.

**Shader Waves** · [GitHub](https://github.com/SamZombie/ShaderWaves)
*Unity, HLSL*

- Implemented real-time procedural ocean waves via direct HLSL shader programming (no Shader Graph), building the water surface from a sum-of-sines displacement model computed on the GPU.
- Derived surface normals and lighting from partial derivatives of the displacement function, working from first principles rather than using Unity's built-in tools.
- Undertaken as a graphics-programming fundamentals project, inspired by Jasper Flick's Catlike Coding series and Garrett Gunnell's water rendering work.

</details>

<details markdown="1">
<summary><strong>Activities</strong></summary>

**Assistant Market Manager (Volunteer)** — Mount Shasta Farmers Market, Mount Shasta, CA
*2020 – 2021*

- Opened and closed the market weekly across its ~22-week May–October season (arriving 30 min early, staying 30 min late): drove routes to place advertising signage, set up entrance, Market Match, and merchandise tents, and coordinated city-provided road-closure signage.
- Staffed an entrance checkpoint enforcing a 100-person capacity limit under COVID-19 restrictions, for a market serving 500–1,000 patrons weekly.
- Trained and directed ~3 fellow volunteers on setup and breakdown procedures.

**Social Chair — Mixed Ultimate Frisbee** — Vassar College, Poughkeepsie, NY
*Aug 2022 – May 2026*

- Served as Social Chair for the Mixed Ultimate Frisbee team, one of 3 Vassar Ultimate programs; attended weekly leadership and social-chair meetings, coordinating with the other two teams' social chairs to plan joint social events for 150+ students across all three programs.
- Planned and executed the social program for the team's annual fall home invitational, hosting 7–10 visiting colleges for a weekend tournament.
- Organized 7 consecutive nightly social events during the team's week-long spring tournament trip to Myrtle Beach, SC.

</details>

<details markdown="1">
<summary><strong>Skills</strong></summary>

**Languages:** Python, Java, C, C++, C#, OCaml

**ML/AI & Data:** PyTorch, HuggingFace Transformers, DistilBERT, scikit-learn, Stable Baselines3, OpenAI Gym, LangChain, Ollama, Qdrant, pandas, yt-project

**Systems & Tools:** RISC-V (Computer Organization), Docker, FastAPI, Streamlit, GitHub Actions, PyMuPDF, Unity, Microsoft Copilot Studio, PyGames

**Coursework/Certifications:** Anthropic Academy — AI Fluency: Framework & Foundations; Claude 101

**Human Languages:** Spanish (Intermediate), Danish (Beginner)

</details>