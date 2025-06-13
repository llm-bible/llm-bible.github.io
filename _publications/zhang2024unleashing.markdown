---
layout: publication
title: 'Llmtreerec: Unleashing The Power Of Large Language Models For Cold-start Recommendations'
authors: Wenlin Zhang, Chuhan Wu, Xiangyang Li, Yuhao Wang, Kuicai Dong, Yichao Wang, Xinyi Dai, Xiangyu Zhao, Huifeng Guo, Ruiming Tang
conference: "COLING 2025"
year: 2024
bibkey: zhang2024unleashing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.00702"}
  - {name: "Code", url: "https://github.com/Applied-Machine-Learning-Lab/LLMTreeRec"}
tags: ['Tools', 'Efficiency and Optimization', 'Reinforcement Learning', 'Training Techniques', 'Has Code']
---
The lack of training data gives rise to the system cold-start problem in
recommendation systems, making them struggle to provide effective
recommendations. To address this problem, Large Language Models (LLMs) can
model recommendation tasks as language analysis tasks and provide zero-shot
results based on their vast open-world knowledge. However, the large scale of
the item corpus poses a challenge to LLMs, leading to substantial token
consumption that makes it impractical to deploy in real-world recommendation
systems. To tackle this challenge, we introduce a tree-based LLM recommendation
framework LLMTreeRec, which structures all items into an item tree to improve
the efficiency of LLM's item retrieval. LLMTreeRec achieves state-of-the-art
performance under the system cold-start setting in two widely used datasets,
which is even competitive with conventional deep recommendation systems that
use substantial training data. Furthermore, LLMTreeRec outperforms the baseline
model in A/B testing on Huawei industrial systems. Consequently, LLMTreeRec
demonstrates its effectiveness as an industry-friendly solution that has been
successfully deployed online. Our code is available at:
https://github.com/Applied-Machine-Learning-Lab/LLMTreeRec.
