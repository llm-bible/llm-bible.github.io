---
layout: publication
title: 'RMB: Comprehensively Benchmarking Reward Models In LLM Alignment'
authors: Enyu Zhou, Guodong Zheng, Binghai Wang, Zhiheng Xi, Shihan Dou, Rong Bao, Wei Shen, Limao Xiong, Jessica Fan, Yurong Mou, Rui Zheng, Tao Gui, Qi Zhang, Xuanjing Huang
conference: "Arxiv"
year: 2024
bibkey: zhou2024comprehensively
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.09893"}
  - {name: "Code", url: "https://github.com/Zhou-Zoey/RMB-Reward-Model-Benchmark"}
tags: ['Efficiency and Optimization', 'Has Code', 'Reinforcement Learning']
---
Reward models (RMs) guide the alignment of large language models (LLMs),
steering them toward behaviors preferred by humans. Evaluating RMs is the key
to better aligning LLMs. However, the current evaluation of RMs may not
directly correspond to their alignment performance due to the limited
distribution of evaluation data and evaluation methods that are not closely
related to alignment objectives. To address these limitations, we propose RMB,
a comprehensive RM benchmark that covers over 49 real-world scenarios and
includes both pairwise and Best-of-N (BoN) evaluations to better reflect the
effectiveness of RMs in guiding alignment optimization. We demonstrate a
positive correlation between our benchmark and the downstream alignment task
performance. Based on our benchmark, we conduct extensive analysis on the
state-of-the-art RMs, revealing their generalization defects that were not
discovered by previous benchmarks, and highlighting the potential of generative
RMs. Furthermore, we delve into open questions in reward models, specifically
examining the effectiveness of majority voting for the evaluation of reward
models and analyzing the impact factors of generative RMs, including the
influence of evaluation criteria and instructing methods. Our evaluation code
and datasets are available at
https://github.com/Zhou-Zoey/RMB-Reward-Model-Benchmark.
