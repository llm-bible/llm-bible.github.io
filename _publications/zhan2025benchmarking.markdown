---
layout: publication
title: 'Score: Benchmarking Long-chain Reasoning In Commonsense Scenarios'
authors: Weidong Zhan, Yue Wang, Nan Hu, Liming Xiao, Jingyuan Ma, Yuhang Qin, Zheng Li, Yixin Yang, Sirui Deng, Jinkun Ding, Wenhan Ma, Rui Li, Weilin Luo, Qun Liu, Zhifang Sui
conference: "Arxiv"
year: 2025
bibkey: zhan2025benchmarking
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.06218'}
tags: ['RAG', 'Tools', 'Training Techniques']
---
Currently, long-chain reasoning remains a key challenge for large language models (LLMs) because natural texts lack sufficient explicit reasoning data. However, existing benchmarks suffer from limitations such as narrow coverage, short reasoning paths, or high construction costs. We introduce SCoRE (Scenario-based Commonsense Reasoning Evaluation), a benchmark that synthesizes multi-hop questions from scenario schemas of entities, relations, and logical rules to assess long-chain commonsense reasoning. SCoRE contains 100k bilingual (Chinese-English) multiple-choice questions whose reasoning chains span 2-11 hops and are grouped into various difficulty levels. Each question is accompanied by fine-grained knowledge labels, explicit reasoning chains, and difficulty levels for diagnostic evaluation. Evaluation results on cutting-edge LLMs such as o3-mini and Deepseek R1 shows that even the best model attains only 69.78% accuracy on SCoRE (even only 47.91% on the hard set), with errors often stemming from rare knowledge, logical inconsistency, and over-interpretation of simple questions. SCoRE offers a scalable, extensible framework for evaluating and diagnosing the long-chain commonsense reasoning abilities of LLMs and guiding future advances in model design and training.
