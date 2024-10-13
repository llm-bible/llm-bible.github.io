---
layout: publication
title: 'Mitigating Catastrophic Forgetting In Large Language Models With Self-synthesized Rehearsal'
authors: Huang Jianheng, Cui Leyang, Wang Ante, Yang Chengyi, Liao Xinting, Song Linfeng, Yao Junfeng, Su Jinsong
conference: "Arxiv"
year: 2024
bibkey: huang2024mitigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.01244"}
tags: ['Applications', 'In Context Learning', 'Prompting', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Large language models (LLMs) suffer from catastrophic forgetting during
continual learning. Conventional rehearsal-based methods rely on previous
training data to retain the model's ability, which may not be feasible in
real-world applications. When conducting continual learning based on a
publicly-released LLM checkpoint, the availability of the original training
data may be non-existent. To address this challenge, we propose a framework
called Self-Synthesized Rehearsal (SSR) that uses the LLM to generate synthetic
instances for rehearsal. Concretely, we first employ the base LLM for
in-context learning to generate synthetic instances. Subsequently, we utilize
the latest LLM to refine the instance outputs based on the synthetic inputs,
preserving its acquired ability. Finally, we select diverse high-quality
synthetic instances for rehearsal in future stages. Experimental results
demonstrate that SSR achieves superior or comparable performance compared to
conventional rehearsal-based approaches while being more data-efficient.
Besides, SSR effectively preserves the generalization capabilities of LLMs in
general domains.
