---
layout: publication
title: 'Magnitude Pruning Of Large Pretrained Transformer Models With A Mixture Gaussian Prior'
authors: Mingxuan Zhang, Yan Sun, Faming Liang
conference: "Arxiv"
year: 2024
bibkey: zhang2024magnitude
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.00969"}
tags: ['Fine-Tuning', 'Transformer', 'Efficiency and Optimization', 'Applications', 'Model Architecture', 'Reinforcement Learning', 'Pruning', 'Pretraining Methods']
---
Large pretrained transformer models have revolutionized modern AI
applications with their state-of-the-art performance in natural language
processing (NLP). However, their substantial parameter count poses challenges
for real-world deployment. To address this, researchers often reduce model size
by pruning parameters based on their magnitude or sensitivity. Previous
research has demonstrated the limitations of magnitude pruning, especially in
the context of transfer learning for modern NLP tasks. In this paper, we
introduce a new magnitude-based pruning algorithm called mixture Gaussian prior
pruning (MGPP), which employs a mixture Gaussian prior for regularization. MGPP
prunes non-expressive weights under the guidance of the mixture Gaussian prior,
aiming to retain the model's expressive capability. Extensive evaluations
across various NLP tasks, including natural language understanding, question
answering, and natural language generation, demonstrate the superiority of MGPP
over existing pruning methods, particularly in high sparsity settings.
Additionally, we provide a theoretical justification for the consistency of the
sparse transformer, shedding light on the effectiveness of the proposed pruning
method.
