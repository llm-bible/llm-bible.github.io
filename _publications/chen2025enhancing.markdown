---
layout: publication
title: 'Graphgen: Enhancing Supervised Fine-tuning For Llms With Knowledge-driven Synthetic Data Generation'
authors: Zihong Chen, Wanli Jiang, Jinzhe Li, Zhonghang Yuan, Huanjun Kong, Wanli Ouyang, Nanqing Dong
conference: "Arxiv"
year: 2025
bibkey: chen2025enhancing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.20416'}
  - {name: "Code", url: 'https://github.com/open-sciencelab/GraphGen'}
tags: ['Has Code', 'RAG', 'Training Techniques', 'Applications', 'Tools', 'Fine-Tuning', 'Pretraining Methods']
---
Fine-tuning for large language models (LLMs) typically requires substantial amounts of high-quality supervised data, which is both costly and labor-intensive to acquire. While synthetic data generation has emerged as a promising solution, existing approaches frequently suffer from factual inaccuracies, insufficient long-tail coverage, simplistic knowledge structures, and homogenized outputs. To address these challenges, we introduce GraphGen, a knowledge graph-guided framework designed for three key question-answering (QA) scenarios: atomic QA, aggregated QA, and multi-hop QA. It begins by constructing a fine-grained knowledge graph from the source text. It then identifies knowledge gaps in LLMs using the expected calibration error metric, prioritizing the generation of QA pairs that target high-value, long-tail knowledge. Furthermore, GraphGen incorporates multi-hop neighborhood sampling to capture complex relational information and employs style-controlled generation to diversify the resulting QA data. Experimental results on knowledge-intensive tasks under closed-book settings demonstrate that GraphGen outperforms conventional synthetic data methods, offering a more reliable and comprehensive solution to the data scarcity challenge in supervised fine-tuning. The code and data are publicly available at https://github.com/open-sciencelab/GraphGen.
