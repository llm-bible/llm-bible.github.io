---
layout: publication
title: 'Robust Data Watermarking In Language Models By Injecting Fictitious Knowledge'
authors: Xinyue Cui, Johnny Tian-zheng Wei, Swabha Swayamdipta, Robin Jia
conference: "Arxiv"
year: 2025
bibkey: cui2025robust
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.04036"}
tags: ['Tools', 'Applications', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
Data watermarking in language models injects traceable signals, such as
specific token sequences or stylistic patterns, into copyrighted text, allowing
copyright holders to track and verify training data ownership. Previous data
watermarking techniques primarily focus on effective memorization after
pretraining, while overlooking challenges that arise in other stages of the LLM
pipeline, such as the risk of watermark filtering during data preprocessing, or
potential forgetting through post-training, or verification difficulties due to
API-only access. We propose a novel data watermarking approach that injects
coherent and plausible yet fictitious knowledge into training data using
generated passages describing a fictitious entity and its associated
attributes. Our watermarks are designed to be memorized by the LLM through
seamlessly integrating in its training data, making them harder to detect
lexically during preprocessing. We demonstrate that our watermarks can be
effectively memorized by LLMs, and that increasing our watermarks' density,
length, and diversity of attributes strengthens their memorization. We further
show that our watermarks remain robust throughout LLM development, maintaining
their effectiveness after continual pretraining and supervised finetuning.
Finally, we show that our data watermarks can be evaluated even under API-only
access via question answering.
