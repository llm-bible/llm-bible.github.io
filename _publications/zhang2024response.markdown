---
layout: publication
title: 'REAL: Response Embedding-based Alignment For Llms'
authors: Honggen Zhang, Xufeng Zhao, Igor Molybog, June Zhang
conference: "Arxiv"
year: 2024
bibkey: zhang2024response
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2409.17169'}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Tools', 'Prompting', 'Reinforcement Learning', 'Ethics and Bias']
---
Aligning large language models (LLMs) to human preferences is a crucial step in building helpful and safe AI tools, which usually involve training on supervised datasets. Popular algorithms such as Direct Preference Optimization (DPO) rely on pairs of AI-generated responses ranked according to human annotation. The response pair annotation process might bring human bias. Building a correct preference dataset is the costly part of the alignment pipeline. To improve annotation efficiency and quality in the LLMs alignment, we propose REAL: Response Embedding-based Alignment for LLMs, a strategy for constructing a high-quality training dataset that focuses on acquiring the less ambiguous preference pairs for labeling out of a set of response candidates. Our selection process is based on the similarity of embedding responses independently of prompts, which guarantees the selection process in an off-policy setting, avoiding adaptively measuring the similarity during the training. Experimental results on real-world dataset SHP2 and synthetic HH-RLHF benchmarks indicate that choosing dissimilar response pairs enhances the direct alignment of LLMs while reducing inherited labeling errors. The model aligned with dissimilar response pairs obtained a better margin and win rate on the dialogue task. Our findings suggest that focusing on distinct pairs can reduce the label error and improve LLM alignment efficiency, saving up to \\(65%\\) of annotators' work.
