---
layout: publication
title: 'Parameter-efficient Fine-tuning Of Large Language Models Using Semantic Knowledge Tuning'
authors: Nusrat Jahan Prottasha, Asif Mahmud, Md. Shohanur Islam Sobuj, Prakash Bhat, Md Kowsher, Niloofar Yousefi, Ozlem Ozmen Garibay
conference: "Arxiv"
year: 2024
bibkey: prottasha2024parameter
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.08598"}
tags: ['Fine-Tuning', 'Efficiency and Optimization', 'Training Techniques', 'Pretraining Methods', 'Prompting']
---
Large Language Models (LLMs) are gaining significant popularity in recent
years for specialized tasks using prompts due to their low computational cost.
Standard methods like prefix tuning utilize special, modifiable tokens that
lack semantic meaning and require extensive training for best performance,
often falling short. In this context, we propose a novel method called Semantic
Knowledge Tuning (SK-Tuning) for prompt and prefix tuning that employs
meaningful words instead of random tokens. This method involves using a fixed
LLM to understand and process the semantic content of the prompt through
zero-shot capabilities. Following this, it integrates the processed prompt with
the input text to improve the model's performance on particular tasks. Our
experimental results show that SK-Tuning exhibits faster training times, fewer
parameters, and superior performance on tasks such as text classification and
understanding compared to other tuning methods. This approach offers a
promising method for optimizing the efficiency and effectiveness of LLMs in
processing language tasks.
