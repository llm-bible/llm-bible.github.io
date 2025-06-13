---
layout: publication
title: 'A Multi-dimensional Constraint Framework For Evaluating And Improving Instruction Following In Large Language Models'
authors: Junjie Ye, Caishuang Huang, Zhuohan Chen, Wenjie Fu, Chenyuan Yang, Leyi Yang, Yilong Wu, Peng Wang, Meng Zhou, Xiaolong Yang, Tao Gui, Qi Zhang, Zhongchao Shi, Jianping Fan, Xuanjing Huang
conference: "Arxiv"
year: 2025
bibkey: ye2025multi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.07591"}
  - {name: "Code", url: "https://github.com/Junjie-Ye/MulDimIF"}
tags: ['Agentic', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'RAG', 'Has Code', 'Prompting', 'Attention Mechanism']
---
Instruction following evaluates large language models (LLMs) on their ability to generate outputs that adhere to user-defined constraints. However, existing benchmarks often rely on templated constraint prompts, which lack the diversity of real-world usage and limit fine-grained performance assessment. To fill this gap, we propose a multi-dimensional constraint framework encompassing three constraint patterns, four constraint categories, and four difficulty levels. Building on this framework, we develop an automated instruction generation pipeline that performs constraint expansion, conflict detection, and instruction rewriting, yielding 1,200 code-verifiable instruction-following test samples. We evaluate 19 LLMs across seven model families and uncover substantial variation in performance across constraint forms. For instance, average performance drops from 77.67% at Level I to 32.96% at Level IV. Furthermore, we demonstrate the utility of our approach by using it to generate data for reinforcement learning, achieving substantial gains in instruction following without degrading general performance. In-depth analysis indicates that these gains stem primarily from modifications in the model's attention modules parameters, which enhance constraint recognition and adherence. Code and data are available in https://github.com/Junjie-Ye/MulDimIF.
