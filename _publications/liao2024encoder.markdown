---
layout: publication
title: E2LLM Encoder Elongated Large Language Models For Long45;context Understanding And Reasoning
authors: Liao Zihan, Wang Jun, Yu Hang, Wei Lingxiao, Li Jianguo, Wang Jun, Zhang Wei
conference: "Arxiv"
year: 2024
bibkey: liao2024encoder
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.06679"}
tags: ['Applications', 'Efficiency And Optimization', 'Prompting', 'RAG', 'Tools', 'Training Techniques']
---
In the realm of Large Language Models (LLMs) the ability to process long contexts is increasingly crucial for tasks such as multi45;round dialogues code generation and document summarization. This paper addresses the challenges of enhancing the long45;context performance reducing computational complexity and leveraging pretrained models collectively termed the impossible triangle. We introduce E2LLM (Encoder Elongated Large Language Models) a novel approach that effectively navigates this paradox. The method involves splitting long contexts into chunks compressing each into embedding vectors via a pretrained text encoder and utilizing an adapter to align these representations with a decoder45;only LLM. Two training objectives focusing on reconstruction of the encoder output and long45;context instruction fine45;tuning are employed to facilitate the understanding of soft prompts by the LLM. Experimental results demonstrate that E2LLM achieves superior performance in long45;context scenarios while balancing efficiency performance and compatibility with pretrained models. Our framework thus represents a significant advancement in the field contributing to effective long45;text modeling.
