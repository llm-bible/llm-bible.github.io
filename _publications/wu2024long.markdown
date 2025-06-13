---
layout: publication
title: 'Long Context Alignment With Short Instructions And Synthesized Positions'
authors: Wenhao Wu, Yizhong Wang, Yao Fu, Xiang Yue, Dawei Zhu, Sujian Li
conference: "Arxiv"
year: 2024
bibkey: wu2024long
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.03939"}
tags: ['Training Techniques', 'GPT', 'Model Architecture', 'Reinforcement Learning']
---
Effectively handling instructions with extremely long context remains a
challenge for Large Language Models (LLMs), typically necessitating
high-quality long data and substantial computational resources. This paper
introduces Step-Skipping Alignment (SkipAlign), a new technique designed to
enhance the long-context capabilities of LLMs in the phase of alignment without
the need for additional efforts beyond training with original data length.
SkipAlign is developed on the premise that long-range dependencies are
fundamental to enhancing an LLM's capacity of long context. Departing from
merely expanding the length of input samples, SkipAlign synthesizes long-range
dependencies from the aspect of positions indices. This is achieved by the
strategic insertion of skipped positions within instruction-following samples,
which utilizes the semantic structure of the data to effectively expand the
context. Through extensive experiments on base models with a variety of context
window sizes, SkipAlign demonstrates its effectiveness across a spectrum of
long-context tasks. Particularly noteworthy is that with a careful selection of
the base model and alignment datasets, SkipAlign with only 6B parameters
achieves it's best performance and comparable with strong baselines like
GPT-3.5-Turbo-16K on LongBench.
