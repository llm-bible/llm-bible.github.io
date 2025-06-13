---
layout: publication
title: 'Mergebench: A Benchmark For Merging Domain-specialized Llms'
authors: Yifei He, Siqi Zeng, Yuzheng Hu, Rui Yang, Tong Zhang, Han Zhao
conference: "Arxiv"
year: 2025
bibkey: he2025benchmark
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.10833'}
  - {name: "Code", url: 'https://github.com/uiuctml/MergeBench}{https://github.com/uiuctml/MergeBench'}
tags: ['Has Code', 'Efficiency and Optimization', 'Training Techniques', 'Merging', 'Pruning', 'Responsible AI']
---
Model merging provides a scalable alternative to multi-task training by combining specialized finetuned models through parameter arithmetic, enabling efficient deployment without the need for joint training or access to all task data. While recent methods have shown promise, existing evaluations are limited in both model scale and task diversity, leaving open questions about their applicability to large, domain-specialized LLMs. To tackle the challenges, we introduce MergeBench, a comprehensive evaluation suite designed to assess model merging at scale. MergeBench builds on state-of-the-art open-source language models, including Llama and Gemma families at 2B to 9B scales, and covers five key domains: instruction following, mathematics, multilingual understanding, coding and safety. We standardize finetuning and evaluation protocols, and assess eight representative merging methods across multi-task performance, forgetting and runtime efficiency. Based on extensive experiments, we provide practical guidelines for algorithm selection and share insights showing that model merging tends to perform better on stronger base models, with techniques such as merging coefficient tuning and sparsification improving knowledge retention. However, several challenges remain, including the computational cost on large models, the gap for in-domain performance compared to multi-task models, and the underexplored role of model merging in standard LLM training pipelines. We hope MergeBench provides a foundation for future research to advance the understanding and practical application of model merging. We open source our code at \href\{https://github.com/uiuctml/MergeBench\}\{https://github.com/uiuctml/MergeBench\}.
