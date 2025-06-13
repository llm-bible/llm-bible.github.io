---
layout: publication
title: 'First Token Probability Guided RAG For Telecom Question Answering'
authors: Tingwei Chen, Jiayi Chen, Zijian Zhao, Haolong Chen, Liang Zhang, Guangxu Zhu
conference: "Arxiv"
year: 2025
bibkey: chen2025first
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.06468'}
tags: ['Attention Mechanism', 'RAG', 'Model Architecture', 'Applications', 'Tools', 'Reinforcement Learning']
---
Large Language Models (LLMs) have garnered significant attention for their
impressive general-purpose capabilities. For applications requiring intricate
domain knowledge, Retrieval-Augmented Generation (RAG) has shown a distinct
advantage in incorporating domain-specific information into LLMs. However,
existing RAG research has not fully addressed the challenges of Multiple Choice
Question Answering (MCQA) in telecommunications, particularly in terms of
retrieval quality and mitigating hallucinations. To tackle these challenges, we
propose a novel first token probability guided RAG framework. This framework
leverages confidence scores to optimize key hyperparameters, such as chunk
number and chunk window size, while dynamically adjusting the context. Our
method starts by retrieving the most relevant chunks and generates a single
token as the potential answer. The probabilities of all options are then
normalized to serve as confidence scores, which guide the dynamic adjustment of
the context. By iteratively optimizing the hyperparameters based on these
confidence scores, we can continuously improve RAG performance. We conducted
experiments to validate the effectiveness of our framework, demonstrating its
potential to enhance accuracy in domain-specific MCQA tasks.
