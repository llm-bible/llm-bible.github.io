---
layout: publication
title: 'Teaching Language Models To Self-improve By Learning From Language Feedback'
authors: Hu Chi, Hu Yimin, Cao Hang, Xiao Tong, Zhu Jingbo
conference: "Arxiv"
year: 2024
bibkey: hu2024teaching
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.07168"}
tags: ['Fine Tuning', 'GPT', 'Model Architecture', 'RAG', 'Uncategorized']
---
Aligning Large Language Models (LLMs) with human intentions and values is crucial yet challenging. Current methods primarily rely on human preferences, which are costly and insufficient in capturing nuanced feedback expressed in natural language. In this paper, we present Self-Refinement Tuning (SRT), a method that leverages model feedback for alignment, thereby reducing reliance on human annotations. SRT uses a base language model (e.g., Tulu2) to generate initial responses, which are critiqued and refined by a more advanced model (e.g., GPT-4-Turbo). This process enables the base model to self-evaluate and improve its outputs, facilitating continuous learning. SRT further optimizes the model by learning from its self-generated feedback and refinements, creating a feedback loop that promotes model improvement. Our empirical evaluations demonstrate that SRT significantly outperforms strong baselines across diverse tasks and model sizes. When applied to a 70B parameter model, SRT increases the win rate from 9.6\&#37; to 25.8\&#37; on the AlpacaEval 2.0 benchmark, surpassing well-established systems such as GPT-4-0314, Claude 2, and Gemini. Our analysis highlights the crucial role of language feedback in the success of SRT, suggesting potential for further exploration in this direction.
