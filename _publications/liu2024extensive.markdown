---
layout: publication
title: Extensive Self45;contrast Enables Feedback45;free Language Model Alignment
authors: Liu Xiao, Song Xixuan, Dong Yuxiao, Tang Jie
conference: "Arxiv"
year: 2024
bibkey: liu2024extensive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.00604"}
  - {name: "Code", url: "https://github.com/THUDM/Self&#45;Contrast"}
tags: ['Agentic', 'Applications', 'Efficiency And Optimization', 'Fine Tuning', 'Has Code', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Reinforcement learning from human feedback (RLHF) has been a central technique for recent large language model (LLM) alignment. However its heavy dependence on costly human or LLM45;as45;Judge preference feedback could stymie its wider applications. In this work we introduce Self45;Contrast a feedback45;free large language model alignment method via exploiting extensive self45;generated negatives. With only supervised fine45;tuning (SFT) targets Self45;Contrast leverages the LLM itself to generate massive diverse candidates and harnesses a pre45;trained embedding model to filter multiple negatives according to text similarity. Theoretically we illustrate that in this setting merely scaling negative responses can still effectively approximate situations with more balanced positive and negative preference annotations. Our experiments with direct preference optimization (DPO) on three datasets show that Self45;Contrast could consistently outperform SFT and standard DPO training by large margins. And as the number of self45;generated negatives increases the performance of Self45;Contrast continues to grow. Code and data are available at https://github.com/THUDM/Self&#45;Contrast.
