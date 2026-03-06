---
title: "Efficacy of NER Models on Fiction and Nonfiction Domains"
collection: publications
category: class_projects
permalink: /publication/2025-10-08-Efficacy-of-NER-Models-on-Fiction-and-Nonfiction-Domains
excerpt: 'Final paper co-wrote with Duncan Beauchamp'
date: 2025-10-08
venue: 'CMPU 366 Natural Language Processing'
paperurl: 'http://samzombie.github.io/publications/paper2-NLP-2025.pdf'
slidesurl: 'http://samzombie.github.io/publications/slides2-NLP-2025.pdf'
# citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---

Named Entity Recognition (NER) models are often trained and evaluated on non-literary text, but their narrative structure and invented entities make literary fiction a challenge. We evaluate the cross-domain performance of a transformer-based NER model on literary and non-literary text, restricting evaluation to core shared entity types. A pretrained DistilBERT NER baseline shows a substantial performance gap between domains, with markedly lower F1 on literary text. Fine-tuning a DistilBERT model on a mixed-domain training set significantly improves performance on fiction while preserving strong non-fiction results. This indicates that simple mixed-domain fine-tuning substantially improves cross-genre robustness, while persistent errors reflect genre-specific entity distributions and narrative phenomena in literary text.
