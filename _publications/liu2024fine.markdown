---
layout: publication
title: "Adamole: Fine-tuning Large Language Models With Adaptive Mixture Of Low-rank Adaptation Experts"
authors: Liu Zefang, Luo Jiahua
conference: "Arxiv"
year: 2024
bibkey: liu2024fine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.00361"}
tags: ['Fine Tuning', 'Pretraining Methods', 'Training Techniques']
---
We introduce AdaMoLE a novel method for fine-tuning large language models (LLMs) through an Adaptive Mixture of Low-Rank Adaptation (LoRA) Experts. Moving beyond conventional methods that employ a static top-k strategy for activating experts AdaMoLE dynamically adjusts the activation threshold using a dedicated threshold network adaptively responding to the varying complexities of different tasks. By replacing a single LoRA in a layer with multiple LoRA experts and integrating a gating function with the threshold mechanism AdaMoLE effectively selects and activates the most appropriate experts based on the input context. Our extensive evaluations across a variety of commonsense reasoning and natural language processing tasks show that AdaMoLE exceeds baseline performance. This enhancement highlights the advantages of AdaMoLEs adaptive selection of LoRA experts improving model effectiveness without a corresponding increase in the expert count. The experimental validation not only confirms AdaMoLE as a robust approach for enhancing LLMs but also suggests valuable directions for future research in adaptive expert selection mechanisms potentially broadening the scope for optimizing model performance across diverse language processing tasks.
