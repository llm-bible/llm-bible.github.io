---
layout: publication
title: 'Understanding The Collapse Of Llms In Model Editing'
authors: Wanli Yang, Fei Sun, Jiajun Tan, Xinyu Ma, Du Su, Dawei Yin, Huawei Shen
conference: "Arxiv"
year: 2024
bibkey: yang2024understanding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.11263"}
tags: ['Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'GPT', 'Pretraining Methods', 'Transformer']
---
Despite significant progress in model editing methods, their application in
real-world scenarios remains challenging as they often cause large language
models (LLMs) to collapse. Among them, ROME is particularly concerning, as it
could disrupt LLMs with only a single edit. In this paper, we study the root
causes of such collapse. Through extensive analysis, we identify two primary
factors that contribute to the collapse: i) inconsistent handling of prefixed
and unprefixed keys in the parameter update equation may result in very small
denominators, causing excessively large parameter updates; ii) the subject of
collapse cases is usually the first token, whose unprefixed key distribution
significantly differs from the prefixed key distribution in autoregressive
transformers, causing the aforementioned issue to materialize. To validate our
findings, we propose a simple yet effective approach: uniformly using prefixed
keys during editing phase and adding prefixes during testing phase to ensure
the consistency between training and testing. The experimental results show
that the proposed solution can prevent model collapse while maintaining the
effectiveness of the edits.
