---
layout: publication
title: 'R1dacted: Investigating Local Censorship In Deepseek''s R1 Language Model'
authors: Ali Naseh, Harsh Chaudhari, Jaechul Roh, Mingshi Wu, Alina Oprea, Amir Houmansadr
conference: "Arxiv"
year: 2025
bibkey: naseh2025investigating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.12625'}
tags: ['Training Techniques', 'Merging', 'Prompting', 'Ethics and Bias', 'Interpretability']
---
DeepSeek recently released R1, a high-performing large language model (LLM) optimized for reasoning tasks. Despite its efficient training pipeline, R1 achieves competitive performance, even surpassing leading reasoning models like OpenAI's o1 on several benchmarks. However, emerging reports suggest that R1 refuses to answer certain prompts related to politically sensitive topics in China. While existing LLMs often implement safeguards to avoid generating harmful or offensive outputs, R1 represents a notable shift - exhibiting censorship-like behavior on politically charged queries. In this paper, we investigate this phenomenon by first introducing a large-scale set of heavily curated prompts that get censored by R1, covering a range of politically sensitive topics, but are not censored by other models. We then conduct a comprehensive analysis of R1's censorship patterns, examining their consistency, triggers, and variations across topics, prompt phrasing, and context. Beyond English-language queries, we explore censorship behavior in other languages. We also investigate the transferability of censorship to models distilled from the R1 language model. Finally, we propose techniques for bypassing or removing this censorship. Our findings reveal possible additional censorship integration likely shaped by design choices during training or alignment, raising concerns about transparency, bias, and governance in language model deployment.
