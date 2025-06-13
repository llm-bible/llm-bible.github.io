---
layout: publication
title: 'Cross-lingual Consistency: A Novel Inference Framework For Advancing Reasoning In Large Language Models'
authors: Zhiwei Yu, Tuo Li, Changhong Wang, Hui Chen, Lang Zhou
conference: "Arxiv"
year: 2025
bibkey: yu2025cross
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.01857'}
tags: ['Training Techniques', 'Ethics and Bias', 'Tools']
---
Chain-of-thought (CoT) has emerged as a critical mechanism for enhancing
reasoning capabilities in large language models (LLMs), with self-consistency
demonstrating notable promise in boosting performance. However, inherent
linguistic biases in multilingual training corpora frequently cause semantic
drift and logical inconsistencies, especially in sub-10B parameter LLMs
handling complex inference tasks. To overcome these constraints, we propose the
Cross-Lingual Consistency (CLC) framework, an innovative inference paradigm
that integrates multilingual reasoning paths through majority voting to elevate
LLMs' reasoning capabilities. Empirical evaluations on the CMATH dataset reveal
CLC's superiority over the conventional self-consistency method, delivering
9.5%, 6.5%, and 6.0% absolute accuracy gains for DeepSeek-Math-7B-Instruct,
Qwen2.5-Math-7B-Instruct, and Gemma2-9B-Instruct respectively. Expanding CLC's
linguistic scope to 11 diverse languages implies two synergistic benefits: 1)
neutralizing linguistic biases in multilingual training corpora through
multilingual ensemble voting, 2) escaping monolingual reasoning traps by
exploring the broader multilingual solution space. This dual benefits
empirically enables more globally optimal reasoning paths compared to
monolingual self-consistency baselines, as evidenced by the 4.1%-18.5% accuracy
gains using Gemma2-9B-Instruct on the MGSM dataset.
