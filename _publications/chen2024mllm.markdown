---
layout: publication
title: 'MLLM Is A Strong Reranker: Advancing Multimodal Retrieval-augmented Generation Via Knowledge-enhanced Reranking And Noise-injected Training'
authors: Zhanpeng Chen, Chengjin Xu, Yiyan Qi, Jian Guo
conference: "Arxiv"
year: 2024
bibkey: chen2024mllm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.21439"}
  - {name: "Code", url: "https://github.com/IDEA-FinAI/RagVL"}
tags: ['Security', 'Training Techniques', 'Multimodal Models', 'Tools', 'Reinforcement Learning', 'RAG', 'Has Code']
---
Multimodal Large Language Models (MLLMs) have demonstrated remarkable
capabilities in processing and generating content across multiple data
modalities. However, a significant drawback of MLLMs is their reliance on
static training data, leading to outdated information and limited contextual
awareness. This static nature hampers their ability to provide accurate and
up-to-date responses, particularly in dynamic or rapidly evolving contexts.
Though integrating Multimodal Retrieval-augmented Generation (Multimodal RAG)
offers a promising solution, the system would inevitably encounter the
multi-granularity noisy correspondence (MNC) problem, which hinders accurate
retrieval and generation. In this work, we propose RagVL, a novel framework
with knowledge-enhanced reranking and noise-injected training, to address these
limitations. We instruction-tune the MLLM with a simple yet effective
instruction template to induce its ranking ability and serve it as a reranker
to precisely filter the top-k retrieved images. For generation, we inject
visual noise during training at the data and token levels to enhance the
generator's robustness. Extensive experiments on the subsets of two datasets
that require retrieving and reasoning over images to answer a given query
verify the effectiveness of our method. Code and models are available at
https://github.com/IDEA-FinAI/RagVL.
