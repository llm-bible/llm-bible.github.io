---
layout: publication
title: 'Knowcoder-x: Boosting Multilingual Information Extraction Via Code'
authors: Yuxin Zuo, Wenxuan Jiang, Wenxuan Liu, Zixuan Li, Long Bai, Hanbin Wang, Yutao Zeng, Xiaolong Jin, Jiafeng Guo, Xueqi Cheng
conference: "Arxiv"
year: 2024
bibkey: zuo2024knowcoder
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.04794"}
  - {name: "Code", url: "https://github.com/ICT-GoKnow/KnowCoder"}
tags: ['Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'GPT', 'Has Code', 'Applications']
---
Empirical evidence indicates that LLMs exhibit spontaneous cross-lingual alignment. However, although LLMs show promising cross-lingual alignment in Information Extraction (IE), a significant imbalance across languages persists, highlighting an underlying deficiency. To address this, we propose KnowCoder-X, a powerful code LLM with advanced cross-lingual and multilingual capabilities for universal IE. Firstly, it standardizes the representation of multilingual schemas using Python classes, ensuring a consistent ontology across different languages. Then, IE across languages is formulated as a unified code generation task. Secondly, we conduct IE cross-lingual alignment instruction tuning on the translated instance prediction task to enhance the model's cross-lingual transferability. During this phase, we also construct a high-quality and diverse bilingual IE parallel dataset with 257k samples, called ParallelNER, synthesized by our proposed robust three-stage pipeline, with manual annotation to ensure quality. Although without training in 29 unseen languages, KnowCoder-X surpasses ChatGPT by 30.17% and SoTA by 20.03%, thereby demonstrating superior cross-lingual IE capabilities. Comprehensive evaluations on 64 IE benchmarks in Chinese and English under various settings demonstrate that KnowCoder-X significantly enhances cross-lingual IE transfer through boosting the IE alignment. Our code and dataset are available at: https://github.com/ICT-GoKnow/KnowCoder
