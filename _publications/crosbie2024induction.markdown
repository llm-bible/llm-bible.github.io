---
layout: publication
title: Induction Heads As An Essential Mechanism For Pattern Matching In In45;context Learning
authors: Crosbie J., Shutova E.
conference: "Arxiv"
year: 2024
bibkey: crosbie2024induction
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.07011"}
tags: ['Attention Mechanism', 'Model Architecture', 'Prompting']
---
Large language models (LLMs) have shown a remarkable ability to learn and perform complex tasks through in45;context learning (ICL). However a comprehensive understanding of its internal mechanisms is still lacking. This paper explores the role of induction heads in a few45;shot ICL setting. We analyse two state45;of45;the45;art models Llama45;345;8B and InternLM245;20B on abstract pattern recognition and NLP tasks. Our results show that even a minimal ablation of induction heads leads to ICL performance decreases of up to ~3237; for abstract pattern recognition tasks bringing the performance close to random. For NLP tasks this ablation substantially decreases the models ability to benefit from examples bringing few45;shot ICL performance close to that of zero45;shot prompts. We further use attention knockout to disable specific induction patterns and present fine45;grained evidence for the role that the induction mechanism plays in ICL.
