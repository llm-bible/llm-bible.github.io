---
layout: publication
title: 'Adaptive Rectification Sampling For Test-time Compute Scaling'
authors: Zhendong Tan, Xingjun Zhang, Chaoyi Hu, Yancheng Pan, Shaoxun Wang
conference: "Arxiv"
year: 2025
bibkey: tan2025adaptive
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.01317'}
tags: ['Reinforcement Learning', 'RAG']
---
The newly released OpenAI-o1 and DeepSeek-R1 have demonstrated that test-time
scaling can significantly improve model performance, especially in complex
tasks such as logical reasoning. Common test-time scaling methods involve
generating more chain of thoughts (CoTs) or longer CoTs with self-correction.
However, while self-correction can improve performance, it may lead to
significant token waste and reduce readability of the CoT if the reasoning
steps are already correct. To demonstrate that large language models (LLMs) can
rectify errors at a more fine-grained level, we propose Adaptive Rectification
Sampling (AR-Sampling), which can guide the LLMs to self-correction at the
appropriate step. AR-Sampling leverages a process-supervised reward model (PRM)
as a verifier and constructed trigger sentences to guide the model in adaptive
step-level rethinking. Through the experiments on GSM8K and MATH500, it
indicate that our approach enables the models to rethink in more fine-grained
level, improving the accuracy of solutions, while generating a reasonable
number of additional tokens.
