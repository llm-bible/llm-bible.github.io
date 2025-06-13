---
layout: publication
title: 'ANCHOR: Llm-driven News Subject Conditioning For Text-to-image Synthesis'
authors: Aashish Anantha Ramakrishnan, Sharon X. Huang, Dongwon Lee
conference: "Arxiv"
year: 2024
bibkey: ramakrishnan2024llm
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2404.10141'}
tags: ['RAG', 'Training Techniques', 'Applications', 'Fine-Tuning', 'Prompting', 'Reinforcement Learning', 'Pretraining Methods']
---
Text-to-Image (T2I) Synthesis has made tremendous strides in enhancing
synthesized image quality, but current datasets evaluate model performance only
on descriptive, instruction-based prompts. Real-world news image captions take
a more pragmatic approach, providing high-level situational and Named-Entity
(NE) information and limited physical object descriptions, making them
abstractive. To evaluate the ability of T2I models to capture intended subjects
from news captions, we introduce the Abstractive News Captions with High-level
cOntext Representation (ANCHOR) dataset, containing 70K+ samples sourced from 5
different news media organizations. With Large Language Models (LLM) achieving
success in language and commonsense reasoning tasks, we explore the ability of
different LLMs to identify and understand key subjects from abstractive
captions. Our proposed method Subject-Aware Finetuning (SAFE), selects and
enhances the representation of key subjects in synthesized images by leveraging
LLM-generated subject weights. It also adapts to the domain distribution of
news images and captions through custom Domain Fine-tuning, outperforming
current T2I baselines on ANCHOR. By launching the ANCHOR dataset, we hope to
motivate research in furthering the Natural Language Understanding (NLU)
capabilities of T2I models.
