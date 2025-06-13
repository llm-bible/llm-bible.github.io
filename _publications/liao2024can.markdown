---
layout: publication
title: 'Can Large Vision-language Models Correct Semantic Grounding Errors By Themselves?'
authors: Yuan-hong Liao, Rafid Mahmood, Sanja Fidler, David Acuna
conference: "Arxiv"
year: 2024
bibkey: liao2024can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.06510"}
tags: ['Multimodal Models', 'Training Techniques', 'Model Architecture', 'Tools', 'Pretraining Methods', 'Fine-Tuning', 'Prompting']
---
Enhancing semantic grounding abilities in Vision-Language Models (VLMs) often involves collecting domain-specific training data, refining the network architectures, or modifying the training recipes. In this work, we venture into an orthogonal direction and explore whether VLMs can improve their semantic grounding by "receiving" feedback, without requiring in-domain data, fine-tuning, or modifications to the network architectures. We systematically analyze this hypothesis using a feedback mechanism composed of a binary signal. We find that if prompted appropriately, VLMs can utilize feedback both in a single step and iteratively, showcasing the potential of feedback as an alternative technique to improve grounding in internet-scale VLMs. Furthermore, VLMs, like LLMs, struggle to self-correct errors out-of-the-box. However, we find that this issue can be mitigated via a binary verification mechanism. Finally, we explore the potential and limitations of amalgamating these findings and applying them iteratively to automatically enhance VLMs' grounding performance, showing grounding accuracy consistently improves using automated feedback across all models in all settings investigated. Overall, our iterative framework improves semantic grounding in VLMs by more than 15 accuracy points under noise-free feedback and up to 5 accuracy points under a simple automated binary verification mechanism. The project website is hosted at https://andrewliao11.github.io/vlms_feedback
