---
permalink: /
title: "About Me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a recent Computer Science graduate from Vassar College with a minor in Astronomy, interested in graduate research at the intersection of applied machine learning, computational astrophysics, and natural language processing.

My technical work spans several domains. In industry, I built and deployed a production knowledge agent using Microsoft Copilot Studio, giving me hands-on experience with AI systems in real enterprise environments. In research, I have fine-tuned named entity recognition models to generalize across mixed-domain corpora, and conducted big data analysis of magnetohydrodynamic simulations of galactic circumgalactic medium dynamics. I approach systems from first principles rather than accepting them as black boxes — whether that means deriving the physics behind a simulation or understanding why a retrieval pipeline returns the results it does.

My most recent project is an [AI Knowledge Base RAG system](https://github.com/SamZombie/AI-Knowledge-Base-RAG) — a production-style Retrieval-Augmented Generation pipeline for querying government and defense AI policy documents. It runs entirely locally with no cloud dependencies, using Mistral 7B via Ollama, BAAI/bge-large-en-v1.5 embeddings, Qdrant for vector storage, and FastAPI for the REST API. The system includes a custom LLM-as-judge evaluation pipeline achieving 0.95 retrieval recall and 0.92 answer similarity across 10 ground-truth question-answer pairs, visualized in a Streamlit dashboard. The full stack is containerized with Docker Compose and tested with GitHub Actions CI/CD.

Beyond AI engineering, I have experience in graphics programming — including shader development for procedural wave generation using fractional Brownian motion — and game design, having shipped a 2D puzzle game during a semester abroad at DIS Copenhagen. I am also exploring deep reinforcement learning, having trained a PPO-based autonomous driving agent over 16 million timesteps.

I am currently exploring work opportunities in computational astrophysics and AI developement, with interests including galactic simulations, magnetohydrodynamics , named entity recognition, and reinforcement learning. If my work looks relevant to yours, feel free to reach out.

Explore my [portfolio](https://samzombie.github.io/portfolio/) or browse my [publications](https://samzombie.github.io/publications/) to see what I have been building and researching.