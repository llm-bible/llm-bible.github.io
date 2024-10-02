---
layout: publication
title: 'Robust Few-shot Transfer Learning For Knowledge Base Question Answering With Unanswerable Questions'
authors: Sawhney Riya, Bhattacharya Indrajit, Mausam
conference: "Arxiv"
year: 2024
bibkey: sawhney2024robust
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.14313"}
tags: ['Applications', 'Few Shot', 'Fine Tuning', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
Real-world KBQA applications require models that are (1) robust -- e.g., can differentiate between answerable and unanswerable questions, and (2) low-resource -- do not require large training data. Towards this goal, we propose the novel task of few-shot transfer for KBQA with unanswerable questions. We present FUn-FuSIC that extends the state-of-the-art (SoTA) few-shot transfer model for answerable-only KBQA to handle unanswerability. It iteratively prompts an LLM to generate logical forms for the question by providing feedback using a diverse suite of syntactic, semantic and execution guided checks, and adapts self-consistency to assess confidence of the LLM to decide answerability. Experiments over newly constructed datasets show that FUn-FuSIC outperforms suitable adaptations of the SoTA model for KBQA with unanswerability, and the SoTA model for answerable-only few-shot-transfer KBQA.
