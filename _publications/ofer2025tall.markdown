---
layout: publication
title: 'TALL -- A Trainable Architecture For Enhancing LLM Performance In Low-resource Languages'
authors: Moshe Ofer, Orel Zamler, Amos Azaria
conference: "Arxiv"
year: 2025
bibkey: ofer2025tall
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2506.05057'}
tags: ['Transformer', 'RAG', 'Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Fine-Tuning', 'Pretraining Methods']
---
Large Language Models (LLMs) excel in high-resource languages but struggle with low-resource languages due to limited training data. This paper presents TALL (Trainable Architecture for Enhancing LLM Performance in Low-Resource Languages), which integrates an LLM with two bilingual translation models. TALL transforms low-resource inputs into high-resource representations, leveraging the LLM's capabilities while preserving linguistic features through dimension alignment layers and custom transformers. Our experiments on Hebrew demonstrate significant improvements over several baselines, including direct use, naive translation, and fine-tuning approaches. The architecture employs a parameter-efficient strategy, freezing pre-trained components while training only lightweight adapter modules, balancing computational efficiency with performance gains.
