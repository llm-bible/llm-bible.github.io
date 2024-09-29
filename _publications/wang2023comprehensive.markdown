---
layout: publication
title: "TRACE: A Comprehensive Benchmark For Continual Learning In Large Language Models"
authors: Wang Xiao, Zhang Yuansen, Chen Tianze, Gao Songyang, Jin Senjie, Yang Xianjun, Xi Zhiheng, Zheng Rui, Zou Yicheng, Gui Tao, Zhang Qi, Huang Xuanjing
conference: "Arxiv"
year: 2023
bibkey: wang2023comprehensive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.06762"}
tags: ['Applications', 'Reinforcement Learning', 'Responsible AI', 'Training Techniques']
---
Aligned large language models (LLMs) demonstrate exceptional capabilities in task-solving following instructions and ensuring safety. However the continual learning aspect of these aligned LLMs has been largely overlooked. Existing continual learning benchmarks lack sufficient challenge for leading aligned LLMs owing to both their simplicity and the models potential exposure during instruction tuning. In this paper we introduce TRACE a novel benchmark designed to evaluate continual learning in LLMs. TRACE consists of 8 distinct datasets spanning challenging tasks including domain-specific tasks multilingual capabilities code generation and mathematical reasoning. All datasets are standardized into a unified format allowing for effortless automatic evaluation of LLMs. Our experiments show that after training on TRACE aligned LLMs exhibit significant declines in both general ability and instruction-following capabilities. For example the accuracy of llama2-chat 13B on gsm8k dataset declined precipitously from 28.837; to 237; after training on our datasets. This highlights the challenge of finding a suitable tradeoff between achieving performance on specific tasks while preserving the original prowess of LLMs. Empirical findings suggest that tasks inherently equipped with reasoning paths contribute significantly to preserving certain capabilities of LLMs against potential declines. Motivated by this we introduce the Reasoning-augmented Continual Learning (RCL) approach. RCL integrates task-specific cues with meta-rationales effectively reducing catastrophic forgetting in LLMs while expediting convergence on novel tasks.
