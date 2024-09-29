---
layout: publication
title: 'PRCA: Fitting Black-box Large Language Models For Retrieval Question Answering Via Pluggable Reward-driven Contextual Adapter'
authors: Yang Haoyan, Li Zhitao, Zhang Yong, Wang Jianzong, Cheng Ning, Li Ming, Xiao Jing
conference: "Arxiv"
year: 2023
bibkey: yang2023fitting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.18347"}
tags: ['Agentic', 'Applications', 'GPT', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Tools']
---
The Retrieval Question Answering (ReQA) task employs the retrieval-augmented framework composed of a retriever and generator. The generator formulates the answer based on the documents retrieved by the retriever. Incorporating Large Language Models (LLMs) as generators is beneficial due to their advanced QA capabilities but they are typically too large to be fine-tuned with budget constraints while some of them are only accessible via APIs. To tackle this issue and further improve ReQA performance we propose a trainable Pluggable Reward-Driven Contextual Adapter (PRCA) keeping the generator as a black box. Positioned between the retriever and generator in a Pluggable manner PRCA refines the retrieved information by operating in a token-autoregressive strategy via maximizing rewards of the reinforcement learning phase. Our experiments validate PRCAs effectiveness in enhancing ReQA performance on three datasets by up to 2037; improvement to fit black-box LLMs into existing frameworks demonstrating its considerable potential in the LLMs era.
