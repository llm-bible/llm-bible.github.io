---
layout: publication
title: 'Effibench-x: A Multi-language Benchmark For Measuring Efficiency Of Llm-generated Code'
authors: Yuhao Qing, Boyu Zhu, Mingzhe Du, Zhijiang Guo, Terry Yue Zhuo, Qianru Zhang, Jie M. Zhang, Heming Cui, Siu-ming Yiu, Dong Huang, See-kiong Ng, Luu Anh Tuan
conference: "Arxiv"
year: 2025
bibkey: qing2025effibench
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.13004'}
  - {name: "Code", url: 'https://github.com/EffiBench/EffiBench-X.git'}
  - {name: "Code", url: 'https://huggingface.co/datasets/EffiBench/effibench-x'}
tags: ['Has Code', 'RAG', 'Efficiency and Optimization', 'Applications', 'Reinforcement Learning']
---
Existing code generation benchmarks primarily evaluate functional correctness, with limited focus on code efficiency and often restricted to a single language like Python. To address this gap, we introduce EffiBench-X, the first multi-language benchmark designed to measure the efficiency of LLM-generated code. EffiBench-X supports Python, C++, Java, JavaScript, Ruby, and Golang. It comprises competitive programming tasks with human-expert solutions as efficiency baselines. Evaluating state-of-the-art LLMs on EffiBench-X reveals that while models generate functionally correct code, they consistently underperform human experts in efficiency. Even the most efficient LLM-generated solutions (Qwen3-32B) achieve only around \textbf\{62%\} of human efficiency on average, with significant language-specific variations. LLMs show better efficiency in Python, Ruby, and JavaScript than in Java, C++, and Golang. For instance, DeepSeek-R1's Python code is significantly more efficient than its Java code. These results highlight the critical need for research into LLM optimization techniques to improve code efficiency across diverse languages. The dataset and evaluation infrastructure are submitted and available at https://github.com/EffiBench/EffiBench-X.git and https://huggingface.co/datasets/EffiBench/effibench-x.
