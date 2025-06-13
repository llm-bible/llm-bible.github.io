---
layout: publication
title: 'Dissecting Bias In Llms: A Mechanistic Interpretability Perspective'
authors: Bhavik Chandna, Zubair Bashir, Procheta Sen
conference: "Arxiv"
year: 2025
bibkey: chandna2025dissecting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.05166"}
tags: ['Training Techniques', 'Model Architecture', 'GPT', 'Ethics and Bias', 'Pretraining Methods', 'Fine-Tuning', 'Interpretability and Explainability']
---
Large Language Models (LLMs) are known to exhibit social, demographic, and gender biases, often as a consequence of the data on which they are trained. In this work, we adopt a mechanistic interpretability approach to analyze how such biases are structurally represented within models such as GPT-2 and Llama2. Focusing on demographic and gender biases, we explore different metrics to identify the internal edges responsible for biased behavior. We then assess the stability, localization, and generalizability of these components across dataset and linguistic variations. Through systematic ablations, we demonstrate that bias-related computations are highly localized, often concentrated in a small subset of layers. Moreover, the identified components change across fine-tuning settings, including those unrelated to bias. Finally, we show that removing these components not only reduces biased outputs but also affects other NLP tasks, such as named entity recognition and linguistic acceptability judgment because of the sharing of important components with these tasks.
