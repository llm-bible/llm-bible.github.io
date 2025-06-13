---
layout: publication
title: 'Prompt-efficient Fine-tuning For Gpt-like Deep Models To Reduce Hallucination And To Improve Reproducibility In Scientific Text Generation Using Stochastic Optimisation Techniques'
authors: Daniil Sulimov
conference: "Arxiv"
year: 2024
bibkey: sulimov2024prompt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.06445"}
tags: ['Fine-Tuning', 'GPT', 'Applications', 'Model Architecture', 'Reinforcement Learning', 'Language Modeling', 'Training Techniques', 'Pretraining Methods', 'Prompting']
---
Large Language Models (LLMs) are increasingly adopted for complex scientific
text generation tasks, yet they often suffer from limitations in accuracy,
consistency, and hallucination control. This thesis introduces a
Parameter-Efficient Fine-Tuning (PEFT) approach tailored for GPT-like models,
aiming to mitigate hallucinations and enhance reproducibility, particularly in
the computational domain of mass spectrometry. We implemented Low-Rank
Adaptation (LoRA) adapters to refine GPT-2, termed MS-GPT, using a specialized
corpus of mass spectrometry literature. Through novel evaluation methods
applied to LLMs, including BLEU, ROUGE, and Perplexity scores, the fine-tuned
MS-GPT model demonstrated superior text coherence and reproducibility compared
to the baseline GPT-2, confirmed through statistical analysis with the Wilcoxon
rank-sum test. Further, we propose a reproducibility metric based on cosine
similarity of model outputs under controlled prompts, showcasing MS-GPT's
enhanced stability. This research highlights PEFT's potential to optimize LLMs
for scientific contexts, reducing computational costs while improving model
reliability.
