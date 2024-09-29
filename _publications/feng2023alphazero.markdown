---
layout: publication
title: Alphazero45;like Tree45;search Can Guide Large Language Model Decoding And Training
authors: Feng Xidong, Wan Ziyu, Wen Muning, Mcaleer Stephen Marcus, Wen Ying, Zhang Weinan, Wang Jun
conference: "Arxiv"
year: 2023
bibkey: feng2023alphazero
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.17179"}
tags: ['Pretraining Methods', 'Prompting', 'RAG', 'Tools', 'Training Techniques']
---
Recent works like Tree45;of45;Thought (ToT) and Reasoning via Planning (RAP) aim to augment the reasoning capabilities of LLMs by using tree45;search algorithms to guide multi45;step reasoning. These methods rely on prompting a pre45;trained model to serve as a value function and focus on problems with low search depth. As a result these methods will not work in domains where the pre45;trained LLM does not have enough knowledge to serve as an effective value function or in domains that require long45;horizon planning. To address these limitations we present an AlphaZero45;like tree45;search learning framework for LLMs (termed TS45;LLM) systematically illustrating how tree45;search with a learned value function can guide LLM decoding. TS45;LLM distinguishes itself in two key ways. (1) Leveraging a learned value function and AlphaZero45;like algorithms our approach can be generally adaptable to a wide range of tasks language models of any size and tasks of varying search depths. (2) Our approach can guide LLMs during both inference and training iteratively improving the LLM. Empirical results across reasoning planning alignment and decision45;making tasks show that TS45;LLM outperforms existing approaches and can handle trees with a depth of 64.
