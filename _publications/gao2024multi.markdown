---
layout: publication
title: 'Multi-modal Agent Tuning: Building A Vlm-driven Agent For Efficient Tool Usage'
authors: Zhi Gao, Bofei Zhang, Pengxiang Li, Xiaojian Ma, Tao Yuan, Yue Fan, Yuwei Wu, Yunde Jia, Song-chun Zhu, Qing Li
conference: "Arxiv"
year: 2024
bibkey: gao2024multi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.15606"}
tags: ['Agentic', 'Multimodal Models', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'GPT', 'Prompting']
---
The advancement of large language models (LLMs) prompts the development of
multi-modal agents, which are used as a controller to call external tools,
providing a feasible way to solve practical tasks. In this paper, we propose a
multi-modal agent tuning method that automatically generates multi-modal
tool-usage data and tunes a vision-language model (VLM) as the controller for
powerful tool-usage reasoning. To preserve the data quality, we prompt the
GPT-4o mini model to generate queries, files, and trajectories, followed by
query-file and trajectory verifiers. Based on the data synthesis pipeline, we
collect the MM-Traj dataset that contains 20K tasks with trajectories of tool
usage. Then, we develop the T3-Agent via \underline\{T\}rajectory
\underline\{T\}uning on VLMs for \underline\{T\}ool usage using MM-Traj.
Evaluations on the GTA and GAIA benchmarks show that the T3-Agent consistently
achieves improvements on two popular VLMs: MiniCPM-V-8.5B and \{Qwen2-VL-7B\},
which outperforms untrained VLMs by \\(20%\\), showing the effectiveness of the
proposed data synthesis pipeline, leading to high-quality data for tool-usage
capabilities.
