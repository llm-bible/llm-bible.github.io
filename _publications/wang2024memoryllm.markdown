---
layout: publication
title: MEMORYLLM Towards Self-updatable Large Language Models
authors: Wang Yu, Gao Yifan, Chen Xiusi, Jiang Haoming, Li Shiyang, Yang Jingfeng, Yin Qingyu, Li Zheng, Li Xian, Yin Bing, Shang Jingbo, Mcauley Julian
conference: "Arxiv"
year: 2024
bibkey: wang2024memoryllm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.04624"}
  - {name: "Code", url: "https://github.com/wangyu-ustc/MemoryLLM"}
tags: ['Has Code', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Transformer']
---
Existing Large Language Models (LLMs) usually remain static after deployment which might make it hard to inject new knowledge into the model. We aim to build models containing a considerable portion of self-updatable parameters enabling the model to integrate new knowledge effectively and efficiently. To this end we introduce MEMORYLLM a model that comprises a transformer and a fixed-size memory pool within the latent space of the transformer. MEMORYLLM can self-update with text knowledge and memorize the knowledge injected earlier. Our evaluations demonstrate the ability of MEMORYLLM to effectively incorporate new knowledge as evidenced by its performance on model editing benchmarks. Meanwhile the model exhibits long-term information retention capacity which is validated through our custom-designed evaluations and long-context benchmarks. MEMORYLLM also shows operational integrity without any sign of performance degradation even after nearly a million memory updates. Our code and model are open-sourced at https://github.com/wangyu-ustc/MemoryLLM.
