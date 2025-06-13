---
layout: publication
title: 'Visual Program Distillation With Template-based Augmentation'
authors: Michal Shlapentokh-rothman, Yu-xiong Wang, Derek Hoiem
conference: "Arxiv"
year: 2024
bibkey: shlapentokhrothman2024visual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.08564"}
tags: ['Prompting', 'Efficiency and Optimization', 'Distillation', 'Applications']
---
Adapting visual programming or prompting large language models (LLMs) to generate executable code for visual tasks like visual question answering (VQA) for specialized tasks or domains remains challenging due to high annotation and inference costs. We propose a low-cost visual program distillation method that can be used for models with at most 1 billion parameters and requires no human-generated program annotations. We achieve this through synthetic data augmentation based on decoupling programs into higher-level skills, called templates, and their corresponding arguments. Experimental results show that, with a relatively small amount of question/answer data, small language models can generate high-quality specialized visual programs with the added benefit of much faster inference
