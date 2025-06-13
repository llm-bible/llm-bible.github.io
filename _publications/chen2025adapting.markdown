---
layout: publication
title: 'Classic4children: Adapting Chinese Literary Classics For Children With Large Language Model'
authors: Jiali Chen, Xusen Hei, Yuqi Xue, Zihan Wu, Jiayuan Xie, Yi Cai
conference: "Arxiv"
year: 2025
bibkey: chen2025adapting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.01090"}
tags: ['Reinforcement Learning']
---
Chinese literary classics hold significant cultural and educational value,
offering deep insights into morality, history, and human nature. These works
often include classical Chinese and complex narratives, making them difficult
for children to read. To bridge this gap, we introduce a child-friendly
literary adaptation (CLA) task to adapt the Chinese literary classic into
engaging and accessible text for children. However, recent large language
models (LLMs) overlook children's reading preferences (\ie, vivid character
portrayals, concise narrative structures, and appropriate readability), which
poses challenges in CLA. In this paper, we propose a method called
InstructChild, which augments the LLM with these preferences for adaptation.
Specifically, we first obtain the characters' personalities and narrative
structure as additional information for fine-grained instruction tuning. Then,
we devise a readability metric as the reward to align the LLM with the
children's reading level. Finally, a lookahead decoding strategy is applied to
improve the readability of the generated text during inference. To support the
evaluation of CLA task, we construct the Classic4Children dataset, which
comprises both the original and child-friendly versions of the Four Great
Classical Novels of Chinese literature. Experimental results show that our
InstructChild significantly improves automatic and human evaluation
performance.
