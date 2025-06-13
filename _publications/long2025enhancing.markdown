---
layout: publication
title: 'Enhancing Large Language Models With Reward-guided Tree Search For Knowledge Graph Question And Answering'
authors: Xiao Long, Liansheng Zhuang, Chen Shen, Shaotian Yan, Yifei Li, Shafei Wang
conference: "Arxiv"
year: 2025
bibkey: long2025enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.12476"}
tags: ['Fine-Tuning', 'Tools', 'Applications', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Recently, large language models (LLMs) have demonstrated impressive performance in Knowledge Graph Question Answering (KGQA) tasks, which aim to find answers based on knowledge graphs (KGs) for natural language questions. Existing LLMs-based KGQA methods typically follow the Graph Retrieval-Augmented Generation (GraphRAG) paradigm, which first retrieves reasoning paths from the large KGs, and then generates the answers based on them. However, these methods emphasize the exploration of new optimal reasoning paths in KGs while ignoring the exploitation of historical reasoning paths, which may lead to sub-optimal reasoning paths. Additionally, the complex semantics contained in questions may lead to the retrieval of inaccurate reasoning paths. To address these issues, this paper proposes a novel and training-free framework for KGQA tasks called Reward-guided Tree Search on Graph (RTSoG). RTSoG decomposes an original question into a series of simpler and well-defined sub-questions to handle the complex semantics. Then, a Self-Critic Monte Carlo Tree Search (SC-MCTS) guided by a reward model is introduced to iteratively retrieve weighted reasoning paths as contextual knowledge. Finally, it stacks the weighted reasoning paths according to their weights to generate the final answers. Extensive experiments on four datasets demonstrate the effectiveness of RTSoG. Notably, it achieves 8.7% and 7.0% performance improvement over the state-of-the-art method on the GrailQA and the WebQSP respectively.
