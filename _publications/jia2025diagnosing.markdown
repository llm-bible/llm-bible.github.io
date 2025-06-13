---
layout: publication
title: 'Diagnosing Our Datasets: How Does My Language Model Learn Clinical Information?'
authors: Furong Jia, David Sontag, Monica Agrawal
conference: "Arxiv"
year: 2025
bibkey: jia2025diagnosing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.15024"}
tags: ['Pretraining Methods', 'Training Techniques', 'Applications', 'Reinforcement Learning']
---
Large language models (LLMs) have performed well across various clinical natural language processing tasks, despite not being directly trained on electronic health record (EHR) data. In this work, we examine how popular open-source LLMs learn clinical information from large mined corpora through two crucial but understudied lenses: (1) their interpretation of clinical jargon, a foundational ability for understanding real-world clinical notes, and (2) their responses to unsupported medical claims. For both use cases, we investigate the frequency of relevant clinical information in their corresponding pretraining corpora, the relationship between pretraining data composition and model outputs, and the sources underlying this data. To isolate clinical jargon understanding, we evaluate LLMs on a new dataset MedLingo. Unsurprisingly, we find that the frequency of clinical jargon mentions across major pretraining corpora correlates with model performance. However, jargon frequently appearing in clinical notes often rarely appears in pretraining corpora, revealing a mismatch between available data and real-world usage. Similarly, we find that a non-negligible portion of documents support disputed claims that can then be parroted by models. Finally, we classified and analyzed the types of online sources in which clinical jargon and unsupported medical claims appear, with implications for future dataset composition.
