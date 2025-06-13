---
layout: publication
title: 'LOLA -- An Open-source Massively Multilingual Large Language Model'
authors: Nikit Srivastava, Denis Kuchelev, Tatiana Moteu Ngoli, Kshitij Shetty, Michael Röder, Hamada Zahera, Diego Moussallem, Axel-cyrille Ngonga Ngomo
conference: "Proceedings of the 31st International Conference on Computational Linguistics (COLING 2025) LOLA - An Open-Source Massively Multilingual Large Language Model ACL Anthology https://aclanthology.org/2025.coling-main.428/"
year: 2024
bibkey: srivastava2024lola
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.11272"}
tags: ['Fine-Tuning', 'Transformer', 'Efficiency and Optimization', 'Model Architecture', 'Training Techniques', 'Pretraining Methods']
---
This paper presents LOLA, a massively multilingual large language model
trained on more than 160 languages using a sparse Mixture-of-Experts
Transformer architecture. Our architectural and implementation choices address
the challenge of harnessing linguistic diversity while maintaining efficiency
and avoiding the common pitfalls of multilinguality. Our analysis of the
evaluation results shows competitive performance in natural language generation
and understanding tasks. Additionally, we demonstrate how the learned
expert-routing mechanism exploits implicit phylogenetic linguistic patterns to
potentially alleviate the curse of multilinguality. We provide an in-depth look
at the training process, an analysis of the datasets, and a balanced
exploration of the model's strengths and limitations. As an open-source model,
LOLA promotes reproducibility and serves as a robust foundation for future
research. Our findings enable the development of compute-efficient multilingual
models with strong, scalable performance across languages.
