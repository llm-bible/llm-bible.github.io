---
layout: publication
title: 'Multimodal Tabular Reasoning With Privileged Structured Information'
authors: Jun-peng Jiang, Yu Xia, Hai-long Sun, Shiyin Lu, Qing-guo Chen, Weihua Luo, Kaifu Zhang, De-chuan Zhan, Han-jia Ye
conference: "Arxiv"
year: 2025
bibkey: jiang2025multimodal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.04088"}
tags: ['Tools', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Multimodal Models']
---
Tabular reasoning involves multi-step information extraction and logical inference over tabular data. While recent advances have leveraged large language models (LLMs) for reasoning over structured tables, such high-quality textual representations are often unavailable in real-world settings, where tables typically appear as images. In this paper, we tackle the task of tabular reasoning from table images, leveraging privileged structured information available during training to enhance multimodal large language models (MLLMs). The key challenges lie in the complexity of accurately aligning structured information with visual representations, and in effectively transferring structured reasoning skills to MLLMs despite the input modality gap. To address these, we introduce TabUlar Reasoning with Bridged infOrmation (\{\sc Turbo\}), a new framework for multimodal tabular reasoning with privileged structured tables. \{\sc Turbo\} benefits from a structure-aware reasoning trace generator based on DeepSeek-R1, contributing to high-quality modality-bridged data. On this basis, \{\sc Turbo\} repeatedly generates and selects the advantageous reasoning paths, further enhancing the model's tabular reasoning ability. Experimental results demonstrate that, with limited (\\(9\\)k) data, \{\sc Turbo\} achieves state-of-the-art performance (\\(+7.2%\\) vs. previous SOTA) across multiple datasets.
