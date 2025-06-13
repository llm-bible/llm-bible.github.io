---
layout: publication
title: 'Unibucllm: Harnessing Llms For Automated Prediction Of Item Difficulty And Response Time For Multiple-choice Questions'
authors: Ana-cristina Rogoz, Radu Tudor Ionescu
conference: "Arxiv"
year: 2024
bibkey: rogoz2024harnessing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.13343"}
  - {name: "Code", url: "https://github.com/ana-rogoz/BEA-2024"}
tags: ['Pretraining Methods', 'Model Architecture', 'Transformer', 'Has Code']
---
This work explores a novel data augmentation method based on Large Language
Models (LLMs) for predicting item difficulty and response time of retired USMLE
Multiple-Choice Questions (MCQs) in the BEA 2024 Shared Task. Our approach is
based on augmenting the dataset with answers from zero-shot LLMs (Falcon,
Meditron, Mistral) and employing transformer-based models based on six
alternative feature combinations. The results suggest that predicting the
difficulty of questions is more challenging. Notably, our top performing
methods consistently include the question text, and benefit from the
variability of LLM answers, highlighting the potential of LLMs for improving
automated assessment in medical licensing exams. We make our code available
https://github.com/ana-rogoz/BEA-2024.
