---
layout: publication
title: 'HEARTS: A Holistic Framework For Explainable, Sustainable And Robust Text Stereotype Detection'
authors: Theo King, Zekun Wu, Adriano Koshiyama, Emre Kazim, Philip Treleaven
conference: "NeurIPS Safe Generative AI Workshop 2024; Workshop on Socially Responsible Language Modelling Research 2024"
year: 2024
bibkey: king2024holistic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.11579"}
tags: ['Responsible AI', 'Model Architecture', 'Tools', 'Interpretability', 'BERT', 'Interpretability and Explainability', 'Prompting', 'In-Context Learning']
---
Stereotypes are generalised assumptions about societal groups, and even
state-of-the-art LLMs using in-context learning struggle to identify them
accurately. Due to the subjective nature of stereotypes, where what constitutes
a stereotype can vary widely depending on cultural, social, and individual
perspectives, robust explainability is crucial. Explainable models ensure that
these nuanced judgments can be understood and validated by human users,
promoting trust and accountability. We address these challenges by introducing
HEARTS (Holistic Framework for Explainable, Sustainable, and Robust Text
Stereotype Detection), a framework that enhances model performance, minimises
carbon footprint, and provides transparent, interpretable explanations. We
establish the Expanded Multi-Grain Stereotype Dataset (EMGSD), comprising
57,201 labelled texts across six groups, including under-represented
demographics like LGBTQ+ and regional stereotypes. Ablation studies confirm
that BERT models fine-tuned on EMGSD outperform those trained on individual
components. We then analyse a fine-tuned, carbon-efficient ALBERT-V2 model
using SHAP to generate token-level importance values, ensuring alignment with
human understanding, and calculate explainability confidence scores by
comparing SHAP and LIME outputs...
