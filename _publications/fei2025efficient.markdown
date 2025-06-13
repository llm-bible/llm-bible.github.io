---
layout: publication
title: 'Efficient Prompt Compression With Evaluator Heads For Long-context Transformer Inference'
authors: Weizhi Fei, Xueyan Niu, Guoqing Xie, Yingqing Liu, Bo Bai, Wei Han
conference: "Arxiv"
year: 2025
bibkey: fei2025efficient
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.12959'}
tags: ['Attention Mechanism', 'Transformer', 'RAG', 'Efficiency and Optimization', 'Model Architecture', 'Applications', 'Tools', 'Training Techniques', 'Prompting', 'Pretraining Methods']
---
Although applications involving long-context inputs are crucial for the
effective utilization of large language models (LLMs), they also result in
increased computational costs and reduced performance. To address this
challenge, we propose an efficient, training-free prompt compression method
that retains key information within compressed prompts. We identify specific
attention heads in transformer-based LLMs, which we designate as evaluator
heads, that are capable of selecting tokens in long inputs that are most
significant for inference. Building on this discovery, we develop EHPC, an
Evaluator Head-based Prompt Compression method, which enables LLMs to rapidly
"skim through" input prompts by leveraging only the first few layers with
evaluator heads during the pre-filling stage, subsequently passing only the
important tokens to the model for inference. EHPC achieves state-of-the-art
results across two mainstream benchmarks: prompt compression and long-context
inference acceleration. Consequently, it effectively reduces the complexity and
costs associated with commercial API calls. We further demonstrate that EHPC
attains competitive results compared to key-value cache-based acceleration
methods, thereby highlighting its potential to enhance the efficiency of LLMs
for long-context tasks.
