---
layout: publication
title: 'Longmagpie: A Self-synthesis Method For Generating Large-scale Long-context Instructions'
authors: Chaochen Gao, Xing Wu, Zijia Lin, Debing Zhang, Songlin Hu
conference: "Arxiv"
year: 2025
bibkey: gao2025self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.17134"}
tags: ['Tools']
---
High-quality long-context instruction data is essential for aligning long-context large language models (LLMs). Despite the public release of models like Qwen and Llama, their long-context instruction data remains proprietary. Human annotation is costly and challenging, while template-based synthesis methods limit scale, diversity, and quality. We introduce LongMagpie, a self-synthesis framework that automatically generates large-scale long-context instruction data. Our key insight is that aligned long-context LLMs, when presented with a document followed by special tokens preceding a user turn, auto-regressively generate contextually relevant queries. By harvesting these document-query pairs and the model's responses, LongMagpie produces high-quality instructions without human effort. Experiments on HELMET, RULER, and Longbench v2 demonstrate that LongMagpie achieves leading performance on long-context tasks while maintaining competitive performance on short-context tasks, establishing it as a simple and effective approach for open, diverse, and scalable long-context instruction data synthesis.
