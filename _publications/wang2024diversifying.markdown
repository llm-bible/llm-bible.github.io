---
layout: publication
title: 'Popalign: Diversifying Contrasting Patterns For A More Comprehensive Alignment'
authors: Zekun Moore Wang, Shawn Wang, Kang Zhu, Jiaheng Liu, Ke Xu, Jie Fu, Wangchunshu Zhou, Wenhao Huang
conference: "Arxiv"
year: 2024
bibkey: wang2024diversifying
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.13785'}
tags: ['Security', 'Training Techniques', 'Tools', 'Prompting', 'Reinforcement Learning']
---
Alignment of large language models (LLMs) involves training models on
preference-contrastive output pairs to adjust their responses according to
human preferences. To obtain such contrastive pairs, traditional methods like
RLHF and RLAIF rely on limited contrasting patterns, such as varying model
variants or decoding temperatures. This singularity leads to two issues: (1)
alignment is not comprehensive; and thereby (2) models are susceptible to
jailbreaking attacks. To address these issues, we investigate how to construct
more comprehensive and diversified contrasting patterns to enhance preference
data (RQ1) and verify the impact of the diversification of contrasting patterns
on model alignment (RQ2). For RQ1, we propose PopAlign, a framework that
integrates diversified contrasting patterns across the prompt, model, and
pipeline levels, introducing six contrasting strategies that do not require
additional feedback labeling procedures. Regarding RQ2, we conduct thorough
experiments demonstrating that PopAlign significantly outperforms existing
methods, leading to more comprehensive alignment.
