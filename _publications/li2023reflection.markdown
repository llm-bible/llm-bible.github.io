---
layout: publication
title: 'Reflection-tuning: Data Recycling Improves LLM Instruction-tuning'
authors: Ming Li, Lichang Chen, Jiuhai Chen, Shwai He, Heng Huang, Jiuxiang Gu, Tianyi Zhou
conference: "Arxiv"
year: 2023
bibkey: li2023reflection
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.11716"}
tags: ['Training Techniques', 'Applications', 'ACL', 'Fine-Tuning']
---
Recent advancements in Large Language Models (LLMs) have expanded the
horizons of natural language understanding and generation. Notably, the output
control and alignment with the input of LLMs can be refined through instruction
tuning. However, as highlighted in several studies, low-quality data in the
training set are usually detrimental to instruction tuning, resulting in
inconsistent or even misleading LLM outputs. We propose a novel method, termed
"reflection-tuning," which addresses the problem by self-improvement and
judging capabilities of LLMs. This approach utilizes an oracle LLM to recycle
the original training data by introspecting and enhancing the quality of
instructions and responses in the data. Extensive experiments on widely used
evaluation benchmarks show that LLMs trained with our recycled data outperform
those trained with existing datasets in various benchmarks.
