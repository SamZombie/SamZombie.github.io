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
Weed, CA, USA · [samgshelly@gmail.com](mailto:samgshelly@gmail.com) · [github.com/SamZombie](https://github.com/SamZombie) · [samzombie.github.io](https://samzombie.github.io)

---

## Education

**Vassar College** — Poughkeepsie, NY  
Bachelor of Arts in Computer Science, Minor in Astronomy  
*Aug 2022 - May 2026* | GPA: 3.64 / 4.00

Relevant Coursework: Data Structures and Algorithms, Analysis of Algorithms, Software Design, Compilers, Natural Language Processing, Introduction to Numerical Methods, Robotic Design Competition

**Danish Institute for Study Abroad** — Copenhagen, Denmark  
*January 2025 – May 2025*

Relevant Coursework: Game Development, Artificial Intelligence

---

## Honors

**DataFest 2024** — Best Overall Analysis

---

## Experience

**AI Intern** — Innovative Computing Systems, Los Angeles, CA  
*May 2025 – January 2026*

- Designed and implemented a Microsoft Copilot Studio Knowledge Agent to streamline employee workflows and internal knowledge access.
- Partnered with the COO and engineering team to research, prototype, and deploy the agent, improving information retrieval efficiency across departments.

**Undergraduate Research Assistant** — Vassar College, Poughkeepsie, NY  
*June 2024 – September 2024*

- Investigated turbulence-driven feedback mechanisms affecting magnetic field dynamics and gas outflows in the circumgalactic medium of a simulated Milky Way-type galaxy.
- Utilized magnetohydrodynamic (MHD) modeling via the MAIHEM/FLASH simulation framework to analyze how injected turbulence drives disk instability, magnetic field saturation, and cold gas outflows.
- Collaborated with co-authors to draft, edit, and revise a research paper summarizing findings, presented at the KNAC Undergraduate Symposium.

**Computer Science Dept. Coach** — Vassar College, Poughkeepsie, NY  
*January 2024 – May 2026*

- Mentored students in foundational and advanced computer science concepts, including algorithms and data structures, in Java.
- Assisted students in debugging code, optimizing algorithms, and mastering software development.

---

## Publications

### Conference Papers

**Feedback Driven Magnetic Field Evolution in MW-type Simulated Circumgalactic Medium**  
Param P. Gogia, Umman Azan, **Sam Shelly** — Advisor: Edward Buie II  
*KNAC Undergraduate Symposium Proceedings*, 2024

Investigated the role of turbulence-driven feedback in shaping magnetic field evolution in the circumgalactic medium (CGM) of a simulated Milky Way-type galaxy. Using three MAIHEM MHD simulations (two at solar metallicity, one at 0.3 Z☉), we found that injected turbulent feedback induces late-stage magnetic field saturation via disk instability and outward propagation of cold, highly magnetized gas clouds, while the no-feedback case exhibits steady cubic growth. Results suggest that turbulence not only structures the CGM magnetically but may significantly alter inner galactic dynamics.

[[Paper]](http://samzombie.github.io/publications/paper1-URSI-2024.pdf) · [[Slides]](http://samzombie.github.io/publications/slides1-URSI-2024.pdf)

### Class Projects

**Efficacy of NER Models on Fiction and Nonfiction Domains**  
Duncan Beauchamp, **Sam Shelly**  
*CMPU 366 Natural Language Processing, Vassar College*, 2025

Evaluated cross-domain performance of transformer-based NER models on literary fiction (LitBank) and expository text (OntoNotes). A pretrained DistilBERT baseline showed a substantial F1 gap between domains (∆F1 = 0.37), particularly for ORG and LOC entities in literary text. Fine-tuning on a mixed-domain corpus using oversampling and a literary-only validation set reduced the domain gap to ∆F1 = 0.13, with micro-averaged F1 on fiction rising from 0.26 to 0.72, demonstrating that simple mixed-domain training substantially improves cross-genre robustness.

[[Paper]](http://samzombie.github.io/publications/paper2-NLP-2025.pdf) · [[Slides]](http://samzombie.github.io/publications/slides2-NLP-2025.pdf)

---

## Projects

**AI Knowledge Base RAG** · [GitHub](https://github.com/SamZombie/AI-Knowlege-Base-RAG)  
*Python, FastAPI, LangChain, Qdrant, Ollama, Mistral 7B, BAAI/bge-large-en-v1.5, PyMuPDF, Docker, Streamlit, pytest, GitHub Actions*

A production-style Retrieval-Augmented Generation (RAG) system for natural language querying over a corpus of government and defense AI policy documents, including NIST AI RMF, OMB M-25-21, DoD AI Strategy, and GSA AI compliance materials. Designed to run entirely locally with no cloud dependencies, suited for privacy-sensitive government and defense use cases.

- Ingests PDFs via PyMuPDF with overlapping chunking; embeds using BAAI/bge-large-en-v1.5 (HuggingFace) stored in Qdrant vector database.
- At query time, retrieves top-k semantically similar chunks and generates grounded answers with source citations using Mistral 7B via Ollama.
- Includes a custom LLM-as-judge evaluation pipeline achieving 0.95 retrieval recall and 0.92 answer similarity across 10 ground-truth QA pairs, visualized in a Streamlit dashboard.
- Served through a FastAPI REST API, containerized with Docker Compose, with GitHub Actions CI/CD running linting and unit tests on every commit.

**PPO Driving Algorithm** · [GitHub](https://github.com/SamZombie/Driving-AI)
*Python, stable_baselines3, matplotlib, gymnasium, numpy, pygame*

Trained a 2D autonomous driving agent using Proximal Policy Optimization (PPO) to navigate a course by passing through a sequence of gates, optimizing a reward signal based on driving performance. Trained over approximately 16 million timesteps to develop stable driving behavior. Plans to extend to generalization across varied track layouts and comparative benchmarking against alternative RL algorithms.

**Shader Waves** · [GitHub](https://github.com/SamZombie/ShaderWaves)  
*Unity, HLSL*

Direct shader programming project in Unity generating realistic ocean waves via fractional Brownian motion built from a sum of sines, implemented without Unity's shader graph. Explored the Unity render pipeline from first principles, inspired by Jasper Flick's CatLike Coding series and Garrett Gunnell's water rendering work.

**Nightcrawler** · [GitHub](https://github.com/jaysonkunkel/GDmidterm) · [Play on itch.io](https://samgshelly.itch.io/nightcrawler)  
*Unity, C#*

Original 2D puzzle game created as a game design midterm at DIS:Copenhagen under instructor Jorge Villa Yagüe, built collaboratively with Jayson Kunkel, Marcus Johnson, and Cayla Gililland. Publicly playable on itch.io.

---

## Activities

**Ultimate Frisbee — Leadership / Player** — Vassar College, Poughkeepsie, NY  
*August 2022 – May 2026*

- Demonstrated commitment and discipline through practices, tournaments, and conditioning programs.
- Worked with team captains and school officials to plan social events while maintaining a supportive and inclusive environment.

---

## Skills

**Programming:** Python, Java, C, C#, C++, OCaml

**Tools & Platforms:** GitHub, Microsoft Copilot Studio, Power Apps, Google Workspace, RISC-V, PyTorch, BERT, scikit-learn, Unity, yt-project, Stable Baselines3, OpenAI Gym, HuggingFace Transformers, PyGames, FastAPI, LangChain, Qdrant, Ollama, Docker, Streamlit

**Languages:** Spanish (Intermediate), Danish (Beginner)

**Core Strengths:** Leadership, Research, Communication, Adaptability, Attention to Detail