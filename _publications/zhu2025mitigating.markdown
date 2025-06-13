---
layout: publication
title: 'Mitigating Lost-in-retrieval Problems In Retrieval Augmented Multi-hop Question Answering'
authors: Rongzhi Zhu, Xiangyu Liu, Zequn Sun, Yiwei Wang, Wei Hu
conference: "Arxiv"
year: 2025
bibkey: zhu2025mitigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.14245"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'RAG', 'GPT', 'Applications']
---
In this paper, we identify a critical problem, "lost-in-retrieval", in retrieval-augmented multi-hop question answering (QA): the key entities are missed in LLMs' sub-question decomposition. "Lost-in-retrieval" significantly degrades the retrieval performance, which disrupts the reasoning chain and leads to the incorrect answers. To resolve this problem, we propose a progressive retrieval and rewriting method, namely ChainRAG, which sequentially handles each sub-question by completing missing key entities and retrieving relevant sentences from a sentence graph for answer generation. Each step in our retrieval and rewriting process builds upon the previous one, creating a seamless chain that leads to accurate retrieval and answers. Finally, all retrieved sentences and sub-question answers are integrated to generate a comprehensive answer to the original question. We evaluate ChainRAG on three multi-hop QA datasets - MuSiQue, 2Wiki, and HotpotQA - using three large language models: GPT4o-mini, Qwen2.5-72B, and GLM-4-Plus. Empirical results demonstrate that ChainRAG consistently outperforms baselines in both effectiveness and efficiency.
