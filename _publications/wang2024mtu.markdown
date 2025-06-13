---
layout: publication
title: 'Mtu-bench: A Multi-granularity Tool-use Benchmark For Large Language Models'
authors: Pei Wang, Yanan Wu, Zekun Wang, Jiaheng Liu, Xiaoshuai Song, Zhongyuan Peng, Ken Deng, Chenchen Zhang, Jiakai Wang, Junran Peng, Ge Zhang, Hangyu Guo, Zhaoxiang Zhang, Wenbo Su, Bo Zheng
conference: "Arxiv"
year: 2024
bibkey: wang2024mtu
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.11710'}
tags: ['Reinforcement Learning', 'GPT', 'Tools', 'Model Architecture']
---
Large Language Models (LLMs) have displayed massive improvements in reasoning
and decision-making skills and can hold natural conversations with users.
Recently, many tool-use benchmark datasets have been proposed. However,
existing datasets have the following limitations: (1). Insufficient evaluation
scenarios (e.g., only cover limited tool-use scenes). (2). Extensive evaluation
costs (e.g., GPT API costs). To address these limitations, in this work, we
propose a multi-granularity tool-use benchmark for large language models called
MTU-Bench. For the "multi-granularity" property, our MTU-Bench covers five tool
usage scenes (i.e., single-turn and single-tool, single-turn and multiple-tool,
multiple-turn and single-tool, multiple-turn and multiple-tool, and
out-of-distribution tasks). Besides, all evaluation metrics of our MTU-Bench
are based on the prediction results and the ground truth without using any GPT
or human evaluation metrics. Moreover, our MTU-Bench is collected by
transforming existing high-quality datasets to simulate real-world tool usage
scenarios, and we also propose an instruction dataset called MTU-Instruct data
to enhance the tool-use abilities of existing LLMs. Comprehensive experimental
results demonstrate the effectiveness of our MTU-Bench. Code and data will be
released at https: //github.com/MTU-Bench-Team/MTU-Bench.git.
