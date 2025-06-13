---
layout: publication
title: 'Implicit Reasoning In Transformers Is Reasoning Through Shortcuts'
authors: Tianhe Lin, Jian Xie, Siyu Yuan, Deqing Yang
conference: "Arxiv"
year: 2025
bibkey: lin2025implicit
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.07604'}
tags: ['Transformer', 'Training Techniques', 'Model Architecture', 'GPT', 'Merging', 'Pretraining Methods']
---
Test-time compute is emerging as a new paradigm for enhancing language models' complex multi-step reasoning capabilities, as demonstrated by the success of OpenAI's o1 and o3, as well as DeepSeek's R1. Compared to explicit reasoning in test-time compute, implicit reasoning is more inference-efficient, requiring fewer generated tokens. However, why does the advanced reasoning capability fail to emerge in the implicit reasoning style? In this work, we train GPT-2 from scratch on a curated multi-step mathematical reasoning dataset and conduct analytical experiments to investigate how language models perform implicit reasoning in multi-step tasks. Our findings reveal: 1) Language models can perform step-by-step reasoning and achieve high accuracy in both in-domain and out-of-domain tests via implicit reasoning. However, this capability only emerges when trained on fixed-pattern data. 2) Conversely, implicit reasoning abilities emerging from training on unfixed-pattern data tend to overfit a specific pattern and fail to generalize further. Notably, this limitation is also observed in state-of-the-art large language models. These findings suggest that language models acquire implicit reasoning through shortcut learning, enabling strong performance on tasks with similar patterns while lacking generalization.
