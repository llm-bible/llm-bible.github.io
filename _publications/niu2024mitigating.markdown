---
layout: publication
title: Mitigating Hallucinations In Large Language Models Via Self-refinement-enhanced Knowledge Retrieval
authors: Niu Mengjia, Li Hao, Shi Jie, Haddadi Hamed, Mo Fan
conference: "Arxiv"
year: 2024
bibkey: niu2024mitigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.06545"}
tags: ['Applications', 'RAG', 'Reinforcement Learning']
---
Large language models (LLMs) have demonstrated remarkable capabilities across various domains although their susceptibility to hallucination poses significant challenges for their deployment in critical areas such as healthcare. To address this issue retrieving relevant facts from knowledge graphs (KGs) is considered a promising method. Existing KG-augmented approaches tend to be resource-intensive requiring multiple rounds of retrieval and verification for each factoid which impedes their application in real-world scenarios. In this study we propose Self-Refinement-Enhanced Knowledge Graph Retrieval (Re-KGR) to augment the factuality of LLMs responses with less retrieval efforts in the medical field. Our approach leverages the attribution of next-token predictive probability distributions across different tokens and various model layers to primarily identify tokens with a high potential for hallucination reducing verification rounds by refining knowledge triples associated with these tokens. Moreover we rectify inaccurate content using retrieved knowledge in the post-processing stage which improves the truthfulness of generated responses. Experimental results on a medical dataset demonstrate that our approach can enhance the factual capability of LLMs across various foundational models as evidenced by the highest scores on truthfulness.
