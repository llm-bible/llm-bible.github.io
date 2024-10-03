---
layout: publication
title: 'ARL2: Aligning Retrievers For Black-box Large Language Models Via Self-guided Adaptive Relevance Labeling'
authors: Zhang Lingxi, Yu Yue, Wang Kuan, Zhang Chao
conference: "ACL"
year: 2024
bibkey: zhang2024aligning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.13542"}
  - {name: "Code", url: "https://github.com/zhanglingxi-cs/ARL2"}
tags: ['Fine Tuning', 'Has Code', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Retrieval-augmented generation enhances large language models (LLMs) by incorporating relevant information from external knowledge sources. This enables LLMs to adapt to specific domains and mitigate hallucinations in knowledge-intensive tasks. However, existing retrievers are often misaligned with LLMs due to their separate training processes and the black-box nature of LLMs. To address this challenge, we propose ARL2, a retriever learning technique that harnesses LLMs as labelers. ARL2 leverages LLMs to annotate and score relevant evidence, enabling learning the retriever from robust LLM supervision. Furthermore, ARL2 uses an adaptive self-training strategy for curating high-quality and diverse relevance data, which can effectively reduce the annotation cost. Extensive experiments demonstrate the effectiveness of ARL2, achieving accuracy improvements of 5.4&#37; on NQ and 4.6&#37; on MMLU compared to the state-of-the-art methods. Additionally, ARL2 exhibits robust transfer learning capabilities and strong zero-shot generalization abilities. Our code will be published at \url\{https://github.com/zhanglingxi-cs/ARL2\}.
