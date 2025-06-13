---
layout: publication
title: 'Extensive Self-contrast Enables Feedback-free Language Model Alignment'
authors: Xiao Liu, Xixuan Song, Yuxiao Dong, Jie Tang
conference: "Arxiv"
year: 2024
bibkey: liu2024extensive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.00604"}
  - {name: "Code", url: "https://github.com/THUDM/Self-Contrast"}
tags: ['Agentic', 'Efficiency and Optimization', 'Training Techniques', 'Reinforcement Learning', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Has Code', 'Applications']
---
Reinforcement learning from human feedback (RLHF) has been a central
technique for recent large language model (LLM) alignment. However, its heavy
dependence on costly human or LLM-as-Judge preference feedback could stymie its
wider applications. In this work, we introduce Self-Contrast, a feedback-free
large language model alignment method via exploiting extensive self-generated
negatives. With only supervised fine-tuning (SFT) targets, Self-Contrast
leverages the LLM itself to generate massive diverse candidates, and harnesses
a pre-trained embedding model to filter multiple negatives according to text
similarity. Theoretically, we illustrate that in this setting, merely scaling
negative responses can still effectively approximate situations with more
balanced positive and negative preference annotations. Our experiments with
direct preference optimization (DPO) on three datasets show that, Self-Contrast
could consistently outperform SFT and standard DPO training by large margins.
And as the number of self-generated negatives increases, the performance of
Self-Contrast continues to grow. Code and data are available at
https://github.com/THUDM/Self-Contrast.
