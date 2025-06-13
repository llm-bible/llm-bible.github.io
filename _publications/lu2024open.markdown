---
layout: publication
title: 'TART: An Open-source Tool-augmented Framework For Explainable Table-based Reasoning'
authors: Xinyuan Lu, Liangming Pan, Yubo Ma, Preslav Nakov, Min-yen Kan
conference: "Arxiv"
year: 2024
bibkey: lu2024open
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2409.11724'}
  - {name: "Code", url: 'https://github.com/XinyuanLu00/TART'}
tags: ['Has Code', 'Interpretability and Explainability', 'Security', 'Training Techniques', 'Model Architecture', 'Tools', 'GPT', 'Applications', 'Reinforcement Learning', 'Interpretability']
---
Current Large Language Models (LLMs) exhibit limited ability to understand
table structures and to apply precise numerical reasoning, which is crucial for
tasks such as table question answering (TQA) and table-based fact verification
(TFV). To address these challenges, we introduce our Tool-Augmented Reasoning
framework for Tables (TART), which integrates LLMs with specialized tools. TART
contains three key components: a table formatter to ensure accurate data
representation, a tool maker to develop specific computational tools, and an
explanation generator to maintain explainability. We also present the TOOLTAB
dataset, a new benchmark designed specifically for training LLMs in table-tool
integration. Our experiments indicate that TART achieves substantial
improvements over existing methods (e.g., Chain-of-Thought) by improving both
the precision of data processing and the clarity of the reasoning process.
Notably, TART paired with CodeLlama achieves 90.0% of the accuracy of the
closed-sourced LLM GPT-3.5-turbo, highlighting its robustness in diverse
real-world scenarios. All the code and data are available at
https://github.com/XinyuanLu00/TART.
