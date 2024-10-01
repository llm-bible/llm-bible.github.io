---
layout: publication
title: 'Maferw: Query Rewriting With Multi-aspect Feedbacks For Retrieval-augmented Large Language Models'
authors: Wang Yujing, Zhang Hainan, Pang Liang, Pang Liang, Zheng Hongwei, Zheng Zhiming
conference: "Arxiv"
year: 2024
bibkey: wang2024query
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.17072"}
tags: ['Agentic', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
"In a real-world RAG system, the current query often involves spoken ellipses and ambiguous references from dialogue contexts, necessitating query rewriting to better describe user's information needs. However, traditional context-based rewriting has minimal enhancement on downstream generation tasks due to the lengthy process from query rewriting to response generation. Some researchers try to utilize reinforcement learning with generation feedback to assist the rewriter, but these sparse rewards provide little guidance in most cases, leading to unstable training and generation results. We find that user's needs are also reflected in the gold document, retrieved documents and ground truth. Therefore, by feeding back these multi-aspect dense rewards to query rewriting, more stable and satisfactory responses can be achieved. In this paper, we propose a novel query rewriting method MaFeRw, which improves RAG performance by integrating multi-aspect feedback from both the retrieval process and generated results. Specifically, we first use manual data to train a T5 model for the rewriter initialization. Next, we design three metrics as reinforcement learning feedback: the similarity between the rewritten query and the gold document, the ranking metrics, and ROUGE between the generation and the ground truth. Inspired by RLAIF, we train three kinds of reward models for the above metrics to achieve more efficient training. Finally, we combine the scores of these reward models as feedback, and use PPO algorithm to explore the optimal query rewriting strategy. Experimental results on two conversational RAG datasets demonstrate that MaFeRw achieves superior generation metrics and more stable training compared to baselines."
