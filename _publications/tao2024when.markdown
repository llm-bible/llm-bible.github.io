---
layout: publication
title: When To Trust Llms\: Aligning Confidence With Response Quality
authors: Tao Shuchang, Yao Liuyi, Ding Hanxing, Xie Yuexiang, Cao Qi, Sun Fei, Gao Jinyang, Shen Huawei, Ding Bolin
conference: "Arxiv"
year: 2024
bibkey: tao2024when
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.17287"}
tags: ['Agentic', 'RAG', 'Reinforcement Learning', 'Responsible AI']
---
Despite the success of large language models (LLMs) in natural language generation much evidence shows that LLMs may produce incorrect or nonsensical text. This limitation highlights the importance of discerning when to trust LLMs especially in safety-critical domains. Existing methods often express reliability by confidence level however their effectiveness is limited by the lack of objective guidance. To address this we propose CONfidence-Quality-ORDer-preserving alignment approach (CONQORD) which leverages reinforcement learning guided by a tailored dual-component reward function. This function integrates quality reward and order-preserving alignment reward functions. Specifically the order-preserving reward incentivizes the model to verbalize greater confidence for responses of higher quality to align the order of confidence and quality. Experiments demonstrate that CONQORD significantly improves the alignment performance between confidence and response accuracy without causing over-cautious. Furthermore the aligned confidence provided by CONQORD informs when to trust LLMs and acts as a determinant for initiating the retrieval process of external knowledge. Aligning confidence with response quality ensures more transparent and reliable responses providing better trustworthiness.
