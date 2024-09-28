---
layout: publication
title: LongWriter Unleashing 10000+ Word Generation from Long Context LLMs
authors: Bai Yushi, Zhang Jiajie, Lv Xin, Zheng Linzhi, Zhu Siqi, Hou Lei, Dong Yuxiao, Tang Jie, Li Juanzi
conference: "Arxiv"
year: 2024
bibkey: bai2024longwriter
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.07055"}
  - {name: "Code", url: "https://github.com/THUDM/LongWriter"}
tags: ['ARXIV', 'Agentic', 'Fine Tuning', 'Has Code', 'LLM', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Current long context large language models (LLMs) can process inputs up to 100000 tokens yet struggle to generate outputs exceeding even a modest length of 2000 words. Through controlled experiments we find that the models effective generation length is inherently bounded by the sample it has seen during supervised fine-tuning (SFT). In other words their output limitation is due to the scarcity of long-output examples in existing SFT datasets. To address this we introduce AgentWrite an agent-based pipeline that decomposes ultra-long generation tasks into subtasks enabling off-the-shelf LLMs to generate coherent outputs exceeding 20000 words. Leveraging AgentWrite we construct LongWriter-6k a dataset containing 6000 SFT data with output lengths ranging from 2k to 32k words. By incorporating this dataset into model training we successfully scale the output length of existing models to over 10000 words while maintaining output quality. We also develop LongBench-Write a comprehensive benchmark for evaluating ultra-long generation capabilities. Our 9B parameter model further improved through DPO achieves state-of-the-art performance on this benchmark surpassing even much larger proprietary models. In general our work demonstrates that existing long context LLM already possesses the potential for a larger output window--all you need is data with extended output during model alignment to unlock this capability. Our code models are at https://github.com/THUDM/LongWriter.
