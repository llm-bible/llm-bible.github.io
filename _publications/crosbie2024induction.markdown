---
layout: publication
title: 'Induction Heads As An Essential Mechanism For Pattern Matching In In-context Learning'
authors: Joy Crosbie, Ekaterina Shutova
conference: "Arxiv"
year: 2024
bibkey: crosbie2024induction
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.07011"}
tags: ['Model Architecture', 'Attention Mechanism', 'Few-Shot', 'Prompting', 'In-Context Learning']
---
Large language models (LLMs) have shown a remarkable ability to learn and
perform complex tasks through in-context learning (ICL). However, a
comprehensive understanding of its internal mechanisms is still lacking. This
paper explores the role of induction heads in a few-shot ICL setting. We
analyse two state-of-the-art models, Llama-3-8B and InternLM2-20B on abstract
pattern recognition and NLP tasks. Our results show that even a minimal
ablation of induction heads leads to ICL performance decreases of up to ~32%
for abstract pattern recognition tasks, bringing the performance close to
random. For NLP tasks, this ablation substantially decreases the model's
ability to benefit from examples, bringing few-shot ICL performance close to
that of zero-shot prompts. We further use attention knockout to disable
specific induction patterns, and present fine-grained evidence for the role
that the induction mechanism plays in ICL.
