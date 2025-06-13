---
layout: publication
title: 'Chain-of-thought Matters: Improving Long-context Language Models With Reasoning Path Supervision'
authors: Dawei Zhu, Xiyu Wei, Guangxiang Zhao, Wenhao Wu, Haosheng Zou, Junfeng Ran, Xun Wang, Lin Sun, Xiangzheng Zhang, Sujian Li
conference: "Arxiv"
year: 2025
bibkey: zhu2025chain
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.20790"}
tags: ['RAG', 'Tools', 'Prompting']
---
Recent advances in Large Language Models (LLMs) have highlighted the
challenge of handling long-context tasks, where models need to reason over
extensive input contexts to aggregate target information. While
Chain-of-Thought (CoT) prompting has shown promise for multi-step reasoning,
its effectiveness for long-context scenarios remains underexplored. Through
systematic investigation across diverse tasks, we demonstrate that CoT's
benefits generalize across most long-context scenarios and amplify with
increasing context length. Motivated by this critical observation, we propose
LongRePS, a process-supervised framework that teaches models to generate
high-quality reasoning paths for enhanced long-context performance. Our
framework incorporates a self-sampling mechanism to bootstrap reasoning paths
and a novel quality assessment protocol specifically designed for long-context
scenarios. Experimental results on various long-context benchmarks demonstrate
the effectiveness of our approach, achieving significant improvements over
outcome supervision baselines on both in-domain tasks (+13.6/+3.8 points for
LLaMA/Qwen on MuSiQue) and cross-domain generalization (+9.3/+8.1 points on
average across diverse QA tasks). Our code, data and trained models are made
public to facilitate future research.
