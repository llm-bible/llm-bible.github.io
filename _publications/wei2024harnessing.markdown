---
layout: publication
title: 'Coinmath: Harnessing The Power Of Coding Instruction For Math Llms'
authors: Chengwei Wei, Bin Wang, Jung-jae Kim, Guimei Liu, Nancy F. Chen
conference: "Arxiv"
year: 2024
bibkey: wei2024harnessing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.11699'}
tags: ['Reinforcement Learning', 'RAG', 'Training Techniques']
---
Large Language Models (LLMs) have shown strong performance in solving
mathematical problems, with code-based solutions proving particularly
effective. However, the best practice to leverage coding instruction data to
enhance mathematical reasoning remains underexplored. This study investigates
three key questions: (1) How do different coding styles of mathematical
code-based rationales impact LLMs' learning performance? (2) Can general-domain
coding instructions improve performance? (3) How does integrating textual
rationales with code-based ones during training enhance mathematical reasoning
abilities? Our findings reveal that code-based rationales with concise
comments, descriptive naming, and hardcoded solutions are beneficial, while
improvements from general-domain coding instructions and textual rationales are
relatively minor. Based on these insights, we propose CoinMath, a learning
strategy designed to enhance mathematical reasoning by diversifying the coding
styles of code-based rationales. CoinMath generates a variety of code-based
rationales incorporating concise comments, descriptive naming conventions, and
hardcoded solutions. Experimental results demonstrate that CoinMath
significantly outperforms its baseline model, MAmmoTH, one of the SOTA math
LLMs.
