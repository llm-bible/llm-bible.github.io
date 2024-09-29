---
layout: publication
title: ARL2 Aligning Retrievers For Black45;box Large Language Models Via Self45;guided Adaptive Relevance Labeling
authors: Zhang Lingxi, Yu Yue, Wang Kuan, Zhang Chao
conference: "ACL"
year: 2024
bibkey: zhang2024aligning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.13542"}
  - {name: "Code", url: "https://github.com/zhanglingxi&#45;cs/ARL2&#125;"}
tags: ['Fine Tuning', 'Has Code', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Retrieval45;augmented generation enhances large language models (LLMs) by incorporating relevant information from external knowledge sources. This enables LLMs to adapt to specific domains and mitigate hallucinations in knowledge45;intensive tasks. However existing retrievers are often misaligned with LLMs due to their separate training processes and the black45;box nature of LLMs. To address this challenge we propose ARL2 a retriever learning technique that harnesses LLMs as labelers. ARL2 leverages LLMs to annotate and score relevant evidence enabling learning the retriever from robust LLM supervision. Furthermore ARL2 uses an adaptive self45;training strategy for curating high45;quality and diverse relevance data which can effectively reduce the annotation cost. Extensive experiments demonstrate the effectiveness of ARL2 achieving accuracy improvements of 5.437; on NQ and 4.637; on MMLU compared to the state45;of45;the45;art methods. Additionally ARL2 exhibits robust transfer learning capabilities and strong zero45;shot generalization abilities. Our code will be published at url123;https://github.com/zhanglingxi&#45;cs/ARL2&#125;.
