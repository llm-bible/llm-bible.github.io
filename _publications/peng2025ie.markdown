---
layout: publication
title: 'Cuckoo: An IE Free Rider Hatched By Massive Nutrition In Llm''s Nest'
authors: Letian Peng, Zilong Wang, Feng Yao, Jingbo Shang
conference: "Arxiv"
year: 2025
bibkey: peng2025ie
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.11275"}
tags: ['Training Techniques', 'Few-Shot', 'Pre-Training']
---
Massive high-quality data, both pre-training raw texts and post-training
annotations, have been carefully prepared to incubate advanced large language
models (LLMs). In contrast, for information extraction (IE), pre-training data,
such as BIO-tagged sequences, are hard to scale up. We show that IE models can
act as free riders on LLM resources by reframing next-token *prediction*
into *extraction* for tokens already present in the context. Specifically,
our proposed next tokens extraction (NTE) paradigm learns a versatile IE model,
*Cuckoo*, with 102.6M extractive data converted from LLM's pre-training
and post-training data. Under the few-shot setting, Cuckoo adapts effectively
to traditional and complex instruction-following IE with better performance
than existing pre-trained IE models. As a free rider, Cuckoo can naturally
evolve with the ongoing advancements in LLM data preparation, benefiting from
improvements in LLM training pipelines without additional manual effort.
