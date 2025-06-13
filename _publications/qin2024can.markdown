---
layout: publication
title: 'Sysbench: Can Large Language Models Follow System Messages?'
authors: Yanzhao Qin, Tao Zhang, Tao Zhang, Yanjun Shen, Wenjing Luo, Haoze Sun, Yan Zhang, Yujing Qiao, Weipeng Chen, Zenan Zhou, Wentao Zhang, Bin Cui
conference: "Arxiv"
year: 2024
bibkey: qin2024can
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2408.10943'}
  - {name: "Code", url: 'https://github.com/PKU-Baichuan-MLSystemLab/SysBench'}
tags: ['Has Code', 'Tools', 'Applications']
---
Large Language Models (LLMs) have become instrumental across various
applications, with the customization of these models to specific scenarios
becoming increasingly critical. System message, a fundamental component of
LLMs, is consist of carefully crafted instructions that guide the behavior of
model to meet intended goals. Despite the recognized potential of system
messages to optimize AI-driven solutions, there is a notable absence of a
comprehensive benchmark for evaluating how well LLMs follow system messages. To
fill this gap, we introduce SysBench, a benchmark that systematically analyzes
system message following ability in terms of three limitations of existing
LLMs: constraint violation, instruction misjudgement and multi-turn
instability. Specifically, we manually construct evaluation dataset based on
six prevalent types of constraints, including 500 tailor-designed system
messages and multi-turn user conversations covering various interaction
relationships. Additionally, we develop a comprehensive evaluation protocol to
measure model performance. Finally, we conduct extensive evaluation across
various existing LLMs, measuring their ability to follow specified constraints
given in system messages. The results highlight both the strengths and
weaknesses of existing models, offering key insights and directions for future
research. The open source library SysBench is available at
https://github.com/PKU-Baichuan-MLSystemLab/SysBench.
