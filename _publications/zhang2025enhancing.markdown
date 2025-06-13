---
layout: publication
title: 'Rot: Enhancing Table Reasoning With Iterative Row-wise Traversals'
authors: Xuanliang Zhang, Dingzirui Wang, Keyan Xu, Qingfu Zhu, Wanxiang Che
conference: "Arxiv"
year: 2025
bibkey: zhang2025enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.15110"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'RAG', 'Attention Mechanism']
---
The table reasoning task, crucial for efficient data acquisition, aims to answer questions based on the given table. Recently, reasoning large language models (RLLMs) with Long Chain-of-Thought (Long CoT) significantly enhance reasoning capabilities, leading to brilliant performance on table reasoning. However, Long CoT suffers from high cost for training and exhibits low reliability due to table content hallucinations. Therefore, we propose Row-of-Thought (RoT), which performs iteratively row-wise table traversal, allowing for reasoning extension and reflection-based refinement at each traversal. Scaling reasoning length by row-wise traversal and leveraging reflection capabilities of LLMs, RoT is training-free. The sequential traversal encourages greater attention to the table, thus reducing hallucinations. Experiments show that RoT, using non-reasoning models, outperforms RLLMs by an average of 4.3%, and achieves state-of-the-art results on WikiTableQuestions and TableBench with comparable models, proving its effectiveness. Also, RoT outperforms Long CoT with fewer reasoning tokens, indicating higher efficiency.
