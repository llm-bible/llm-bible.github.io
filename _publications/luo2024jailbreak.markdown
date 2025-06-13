---
layout: publication
title: 'Jailbreak Instruction-tuned Llms Via End-of-sentence MLP Re-weighting'
authors: Yifan Luo, Zhennan Zhou, Meitan Wang, Bin Dong
conference: "Arxiv"
year: 2024
bibkey: luo2024jailbreak
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.10150'}
tags: ['Prompting', 'Security', 'Responsible AI']
---
In this paper, we investigate the safety mechanisms of instruction fine-tuned
large language models (LLMs). We discover that re-weighting MLP neurons can
significantly compromise a model's safety, especially for MLPs in
end-of-sentence inferences. We hypothesize that LLMs evaluate the harmfulness
of prompts during end-of-sentence inferences, and MLP layers plays a critical
role in this process. Based on this hypothesis, we develop 2 novel white-box
jailbreak methods: a prompt-specific method and a prompt-general method. The
prompt-specific method targets individual prompts and optimizes the attack on
the fly, while the prompt-general method is pre-trained offline and can
generalize to unseen harmful prompts. Our methods demonstrate robust
performance across 7 popular open-source LLMs, size ranging from 2B to 72B.
Furthermore, our study provides insights into vulnerabilities of
instruction-tuned LLM's safety and deepens the understanding of the internal
mechanisms of LLMs.
