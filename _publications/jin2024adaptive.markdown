---
layout: publication
title: Adaptive Skeleton Graph Decoding
authors: Jin Shuowei, Wu Yongji, Zheng Haizhong, Zhang Qingzhao, Lentz Matthew, Mao Z. Morley, Prakash Atul, Qian Feng, Zhuo Danyang
conference: "Arxiv"
year: 2024
bibkey: jin2024adaptive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.12280"}
tags: ['GPT', 'Large Scale Training', 'Pretraining Methods', 'Prompting', 'RAG', 'Reinforcement Learning']
---
Large language models (LLMs) have seen significant adoption for natural language tasks owing their success to massive numbers of model parameters (e.g. 70B+); however LLM inference incurs significant computation and memory costs. Recent approaches propose parallel decoding strategies such as Skeleton45;of45;Thought (SoT) to improve performance by breaking prompts down into sub45;problems that can be decoded in parallel; however they often suffer from reduced response quality. Our key insight is that we can request additional information specifically dependencies and difficulty when generating the sub45;problems to improve both response quality and performance. In this paper we propose Skeleton Graph Decoding (SGD) which uses dependencies exposed between sub45;problems to support information forwarding between dependent sub45;problems for improved quality while exposing parallelization opportunities for decoding independent sub45;problems. Additionally we leverage difficulty estimates for each sub45;problem to select an appropriately45;sized model improving performance without significantly reducing quality. Compared to standard autoregressive generation and SoT SGD achieves a 1.69x speedup while improving quality by up to 5137;.
