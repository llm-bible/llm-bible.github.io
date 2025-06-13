---
layout: publication
title: 'Optimizing Instruction Synthesis: Effective Exploration Of Evolutionary Space With Tree Search'
authors: Chenglin Li, Qianglong Chen, Zhi Li, Feng Tao, Yicheng Li, Hao Chen, Fei Yu, Yin Zhang
conference: "Arxiv"
year: 2024
bibkey: li2024optimizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.10392"}
tags: ['Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG', 'Pretraining Methods', 'Fine-Tuning']
---
Instruction tuning is a crucial technique for aligning language models with
humans' actual goals in the real world. Extensive research has highlighted the
quality of instruction data is essential for the success of this alignment.
However, creating high-quality data manually is labor-intensive and
time-consuming, which leads researchers to explore using LLMs to synthesize
data. Recent studies have focused on using a stronger LLM to iteratively
enhance existing instruction data, showing promising results. Nevertheless,
previous work often lacks control over the evolution direction, resulting in
high uncertainty in the data synthesis process and low-quality instructions. In
this paper, we introduce a general and scalable framework, IDEA-MCTS
(Instruction Data Enhancement using Monte Carlo Tree Search), a scalable
framework for efficiently synthesizing instructions. With tree search and
evaluation models, it can efficiently guide each instruction to evolve into a
high-quality form, aiding in instruction fine-tuning. Experimental results show
that IDEA-MCTS significantly enhances the seed instruction data, raising the
average evaluation scores of quality, diversity, and complexity from 2.19 to
3.81. Furthermore, in open-domain benchmarks, experimental results show that
IDEA-MCTS improves the accuracy of real-world instruction-following skills in
LLMs by an average of 5% in low-resource settings.
