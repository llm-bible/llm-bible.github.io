---
layout: publication
title: 'One Missing Piece For Open-source Reasoning Models: A Dataset To Mitigate Cold-starting Short Cot Llms In RL'
authors: Hyungjoo Chae, Dongjin Kang, Jihyuk Kim, Beong-woo Kwak, Sunghyun Park, Haeju Park, Jinyoung Yeo, Moontae Lee, Kyungjae Lee
conference: "Arxiv"
year: 2025
bibkey: chae2025one
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.02338"}
tags: ['Agentic', 'Efficiency and Optimization', 'Training Techniques', 'Reinforcement Learning', 'Distillation']
---
With the release of R1, a publicly available large reasoning model (LRM), researchers commonly train new LRMs by training language models on R1's long chain-of-thought (CoT) inferences. While prior works show that LRMs' capabilities can be reproduced through direct distillation, the continued reliance on the existing models (e.g., R1) remains a critical limitation in advancing the field. As a first step toward independent LRM development, this paper explores the possibility of constructing a long CoT dataset with LLMs that are not trained for inference-time scaling. To this end, we present the Long CoT Collection, a dataset of 100K CoT rationales annotated using existing short CoT LLMs. We develop a pipeline that induces o1's novel reasoning strategies into short CoT LLMs, enabling them to think longer and introducing controllability over the thought budget to better manage the overthinking problem. Our extensive analyses validate that our dataset achieves quality comparable to--or slightly below--R1. Furthermore, our experiments demonstrate that training on our dataset not only strengthens general reasoning skills, but also provides a strong foundation for reinforcement learning--models initialized on our data achieve 2-3x larger gains with RLVR.
