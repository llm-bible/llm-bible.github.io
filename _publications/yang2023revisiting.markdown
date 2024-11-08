---
layout: publication
title: 'Revisiting Parallel Context Windows: A Frustratingly Simple Alternative And Chain-of-thought Deterioration'
authors: Yang Kejuan, Liu Xiao, Men Kaiwen, Zeng Aohan, Dong Yuxiao, Tang Jie
conference: "Arxiv"
year: 2023
bibkey: yang2023revisiting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.15262"}
tags: ['Applications', 'Attention Mechanism', 'Few Shot', 'Model Architecture', 'Reinforcement Learning']
---
We identify two crucial limitations in the evaluation of recent
parallel-integrated method Parallel Context Windows (PCW), which extends the
maximum context lengths of language models, e.g., 2048 for LLaMA, by harnessing
window-wise attention and positional embedding techniques. We first show that a
simple yet strong baseline, weighted sum ensemble, is missing for the
in-context few-shot classification. Moreover, on more challenging
Chain-of-Thought (CoT) reasoning (e.g., HotpotQA), PCW would present unexpected
deterioration regarding question miscomprehension and false inference. Based on
our findings, we suggest that the existing PCW design may not guarantee
sufficient improvement and practicality in handling lengthy documents in
real-world applications. More community efforts on enabling language models'
long context understanding ability should be paid.
