---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

***[Download Resume](https://samzombie.github.io/portfolio/Sam-Shelly-Resume.pdf)***

# Sam Shelly

**Computer Science & Astronomy | Vassar College**
Weed, CA, USA · [samgshelly@gmail.com](mailto:samgshelly@gmail.com) · [linkedin.com/in/sam-g-shelly](https://linkedin.com/in/sam-g-shelly/) · [github.com/SamZombie](https://github.com/SamZombie) · [samzombie.github.io](https://samzombie.github.io)

---

## Education

**Vassar College** — Poughkeepsie, NY
Bachelor of Arts in Computer Science, Minor in Astronomy
*Aug 2022 – May 2026* | GPA: 3.64/4.00 | Major GPA: 3.68/4.00

Relevant Coursework: Data Structures & Algorithms, Analysis of Algorithms, Software Design, Compilers, Theory of Computation, Computer Organization, Natural Language Processing, Numerical Methods, Autonomous Robotics Design

- Diagnosed recurring board failures on an Arduino Uno R4 WiFi-based robot to an undersized battery and mismatched-voltage motors frying the board, as one of two programmers on a 4-person robotics team.
- Built a written technical case — including a full engineering log — proving the failure was caused by faculty-provided component specs rather than team error; presented it to course faculty in a three-hour post-class meeting, and the analysis was accepted, correcting the grade from a C to an A-.

**Danish Institute for Study Abroad** — Copenhagen, Denmark
*Jan 2025 – May 2025*

Coursework: Game Development, Ethics of Artificial Intelligence

- Programmed core movement mechanics and UI for *Nightcrawler*, a 2D puzzle game built in Unity/C# with a 4-person team; published on [itch.io](https://samgshelly.itch.io/nightcrawler).

---

## Experience

**AI Development Intern** — Innovative Computing Systems, Los Angeles, CA
*May 2025 – Jan 2026*

- Hired directly by the COO to lead a Microsoft Copilot Studio Knowledge Agent pilot at a ~60-person company; worked full-time (30 hrs/week) as the primary builder on a 4-person team, meeting weekly with the COO to scope use cases, while three engineers contributed part-time (~5 hrs/week) on team dynamics and use-case input.
- Built Python-based ingestion pipelines to index SharePoint content — including SOPs, the employee handbook, and company org hierarchy — for retrieval, and implemented an API integration connecting the agent to the company's work-ticket system, letting engineers instantly query prior work history on a given client.
- Rolled the agent out to a daily-use focus group and began scoping it for a second prospective external client as part of early efforts to commercialize the tool.

**Undergraduate Research Assistant** — Vassar College, Poughkeepsie, NY
*Jun 2024 – Sep 2024* (Undergraduate Research Summer Institute)

- Analyzed three MAIHEM/FLASH magnetohydrodynamic simulations of a Milky Way-type galaxy's circumgalactic medium (two at solar metallicity, one at 0.3 Z☉) to characterize turbulence-driven magnetic field evolution.
- Built visualizations using yt-project — radial Mach-Alfvén profiles, angular momentum phase plots, and magnetic/kinetic energy density evolution — showing that turbulent feedback drives disk instability and outward propagation of cold, magnetized gas that saturates the CGM's magnetic field, versus steady cubic growth in the no-feedback case.
- Co-authored and wrote roughly half of the resulting paper, presented at the KNAC Undergraduate Symposium 2024, advised by Edward Buie II.

**Computer Science Dept. Coach** — Vassar College, Poughkeepsie, NY
*Jan 2024 – May 2026*

- Selected for a formal, paid CS Dept Coach position (8 hrs/week), retained across 4 consecutive semesters spanning two course iterations under two different instructors.
- Led 3 weekly sessions on algorithms, data structures, and debugging in Java for up to 50 students per semester (200+ total), adapting pacing and session plans for struggling students.

---

## Publications

### Conference Papers

**Feedback-Driven Magnetic Field Evolution in MW-type Simulated Circumgalactic Medium**
Param P. Gogia, Umman Azan, **Sam Shelly** — Advisor: Edward Buie II
*KNAC Undergraduate Symposium Proceedings*, 2024

Investigated turbulence-driven feedback's role in shaping magnetic field evolution in the circumgalactic medium (CGM) of a simulated Milky Way-type galaxy. Using three MAIHEM MHD simulations (two at solar metallicity, one at 0.3 Z☉), found that injected turbulent feedback induces late-stage magnetic field saturation via disk instability and outward propagation of cold, highly magnetized gas clouds, while the no-feedback case exhibits steady cubic growth.

*My contribution: performed the post-simulation analysis (Mach-Alfvén profiles, angular momentum phase plots, magnetic/kinetic energy density evolution), built all data visualizations using yt-project, and wrote ~50% of the manuscript.*

[[Paper]](http://samzombie.github.io/publications/paper1-URSI-2024.pdf) · [[Slides]](http://samzombie.github.io/publications/slides1-URSI-2024.pdf)

### Class Projects

**Efficacy of NER Models on Fiction and Nonfiction Domains**
Duncan Beauchamp, **Sam Shelly**
*CMPU 366 Natural Language Processing, Vassar College*, 2025

Evaluated cross-domain performance of a DistilBERT-based NER model on literary fiction (LitBank) vs. expository text (OntoNotes), restricted to shared PER/LOC/ORG entity types. A pretrained baseline showed a 0.368 F1 domain gap between genres; fine-tuning on a mixed-domain corpus (3× oversampled LitBank, 50-token chunking, literary-only validation split) cut the gap to 0.128, raising LitBank micro-F1 from 0.26 to 0.72.

*My contribution: built the training data pipeline (dataset loading, chunking, oversampling, train/validation/test splits) and wrote ~50% of the manuscript.*

[[Paper]](http://samzombie.github.io/publications/paper2-NLP-2025.pdf) · [[Slides]](http://samzombie.github.io/publications/slides2-NLP-2025.pdf) · [[Code]](https://github.com/d-beauchamp/ner-genre-evaluation)

---

## Projects

**AI Knowledge Base RAG** · [GitHub](https://github.com/SamZombie/AI-Knowledge-Base-RAG)
*Python, FastAPI, LangChain, Qdrant, Ollama, Mistral 7B, BAAI/bge-large-en-v1.5, PyMuPDF, Docker, Streamlit, pytest, GitHub Actions*

A production-style RAG system for querying government/defense AI policy documents (NIST AI RMF, OMB M-25-21, DoD AI Strategy, GSA AI compliance materials). Designed around free, locally-hosted, open-weight components (Mistral 7B, Qdrant) instead of paid hosted APIs, to eliminate cloud dependencies and control cost and data exposure — a deliberate fit for privacy-sensitive government/defense use cases.

- Selected PyMuPDF for PDF ingestion based on its performance reputation and ease of integration; chunks with overlap and embeds via BAAI/bge-large-en-v1.5 into Qdrant.
- Retrieves top-k chunks and generates grounded, cited answers via Mistral 7B (Ollama).
- Built a custom LLM-as-judge evaluation pipeline achieving 0.95 retrieval recall and 0.92 answer similarity across 10 ground-truth QA pairs, visualized in a Streamlit dashboard.
- Served via FastAPI REST API, containerized with Docker Compose, with CI/CD via GitHub Actions.

**DataFest 2024 — Best Overall Analysis**
*Python, pandas | 4-person team, 48-hour competition*

Analyzed student-interaction data (video views, quiz attempts, textbook page views; n≈1,857 students) from an online statistics textbook to advise an ed-tech client on improving learning outcomes.

- Team built a multiple regression model (R²=0.47) identifying quiz effort and video engagement as positive predictors of student performance, and quantified that textbook-only engagement and frequent answer-changing predicted lower scores.
- A teammate built a pandas-based directed dependency graph mapping how students navigated between textbook chapters/sections while studying, informing a recommendation to prepend review material to high-traffic "capstone" chapters.
- Authored the team's final write-up and slide presentation synthesizing both analyses into client-facing recommendations; won Best Overall Analysis over 20 competing teams from 3 schools.

**PPO Driving Algorithm** · [GitHub](https://github.com/SamZombie/Driving-AI)
*Python, stable_baselines3, matplotlib, gymnasium, numpy, pygame*

- Trained a 2D autonomous driving agent via Proximal Policy Optimization to navigate a gated course, achieving a 100% gate-pass rate with an asymptotic S-curve reward convergence over ~16M timesteps.
- Demonstrated policy generalization by extrapolating the trained agent to unseen course layouts.

**Shader Waves** · [GitHub](https://github.com/SamZombie/ShaderWaves)
*Unity, HLSL*

- Implemented real-time procedural ocean waves via direct HLSL shader programming (no Shader Graph), building the water surface from a sum-of-sines displacement model computed on the GPU.
- Derived surface normals and lighting from partial derivatives of the displacement function, working from first principles rather than using Unity's built-in tools.
- Undertaken as a graphics-programming fundamentals project, inspired by Jasper Flick's Catlike Coding series and Garrett Gunnell's water rendering work.

---

## Activities

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

---

## Skills

**Languages:** Python, Java, C, C++, C#, OCaml

**ML/AI & Data:** PyTorch, HuggingFace Transformers, DistilBERT, scikit-learn, Stable Baselines3, OpenAI Gym, LangChain, Ollama, Qdrant, pandas, yt-project

**Systems & Tools:** RISC-V (Computer Organization), Docker, FastAPI, Streamlit, GitHub Actions, PyMuPDF, Unity, Microsoft Copilot Studio, PyGames

**Coursework/Certifications:** Anthropic Academy — AI Fluency: Framework & Foundations; Claude 101

**Human Languages:** Spanish (Intermediate), Danish (Beginner)