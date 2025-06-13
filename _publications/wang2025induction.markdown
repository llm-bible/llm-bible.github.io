---
layout: publication
title: 'Induction Head Toxicity Mechanistically Explains Repetition Curse In Large Language Models'
authors: Shuxun Wang, Qingyu Yin, Chak Tou Leong, Qiang Zhang, Linyi Yang
conference: "Arxiv"
year: 2025
bibkey: wang2025induction
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.13514'}
tags: ['Attention Mechanism', 'Interpretability and Explainability', 'Training Techniques', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'In-Context Learning']
---
Repetition curse is a phenomenon where Large Language Models (LLMs) generate repetitive sequences of tokens or cyclic sequences. While the repetition curse has been widely observed, its underlying mechanisms remain poorly understood. In this work, we investigate the role of induction heads--a specific type of attention head known for their ability to perform in-context learning--in driving this repetitive behavior. Specifically, we focus on the "toxicity" of induction heads, which we define as their tendency to dominate the model's output logits during repetition, effectively excluding other attention heads from contributing to the generation process. Our findings have important implications for the design and training of LLMs. By identifying induction heads as a key driver of the repetition curse, we provide a mechanistic explanation for this phenomenon and suggest potential avenues for mitigation. We also propose a technique with attention head regularization that could be employed to reduce the dominance of induction heads during generation, thereby promoting more diverse and coherent outputs.
