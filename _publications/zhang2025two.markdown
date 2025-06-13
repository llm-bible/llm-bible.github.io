---
layout: publication
title: 'Two-way Evidence Self-alignment Based Dual-gated Reasoning Enhancement'
authors: Kexin Zhang, Junlan Chen, Daifeng Li, Yuxuan Zhang, Yangyang Feng, Bowen Deng, Weixu Chen
conference: "Arxiv"
year: 2025
bibkey: zhang2025two
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.16806'}
  - {name: "Code", url: 'https://anonymous.4open.science/r/ESA-DGR-2BF8'}
tags: ['Has Code', 'RAG', 'Security', 'Training Techniques', 'Tools', 'Fine-Tuning', 'Pretraining Methods']
---
Large language models (LLMs) encounter difficulties in knowledge-intensive multi-step reasoning (KIMSR) tasks. One challenge is how to effectively extract and represent rationale evidence. The current methods often extract semantically relevant but logically irrelevant evidence, resulting in flawed reasoning and inaccurate responses. We propose a two-way evidence self-alignment (TW-ESA) module, which utilizes the mutual alignment between strict reasoning and LLM reasoning to enhance its understanding of the causal logic of evidence, thereby addressing the first challenge. Another challenge is how to utilize the rationale evidence and LLM's intrinsic knowledge for accurate reasoning when the evidence contains uncertainty. We propose a dual-gated reasoning enhancement (DGR) module to gradually fuse useful knowledge of LLM within strict reasoning, which can enable the model to perform accurate reasoning by focusing on causal elements in the evidence and exhibit greater robustness. The two modules are collaboratively trained in a unified framework ESA-DGR. Extensive experiments on three diverse and challenging KIMSR datasets reveal that ESA-DGR significantly surpasses state-of-the-art LLM-based fine-tuning methods, with remarkable average improvements of 4% in exact match (EM) and 5% in F1 score. The implementation code is available at https://anonymous.4open.science/r/ESA-DGR-2BF8.
