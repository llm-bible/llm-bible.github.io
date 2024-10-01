---
layout: publication
title: 'Dynamics Of Instruction Tuning: Each Ability Of Large Language Models Has Its Own Growth Pace'
authors: Song Chiyu, Zhou Zhanchao, Yan Jianhao, Fei Yuejiao, Lan Zhenzhong, Zhang Yue
conference: "Arxiv"
year: 2023
bibkey: song2023dynamics
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.19651"}
tags: ['Applications', 'Efficiency And Optimization', 'GPT', 'Model Architecture', 'Reinforcement Learning']
---
'Instruction tuning is a burgeoning method to elicit the general intelligence of Large Language Models (LLMs). However, the creation of instruction data is still largely heuristic, leading to significant variation in quantity and quality across existing datasets. While some research advocates for expanding the number of instructions, others suggest that a small set of well-chosen examples is adequate. To better understand data construction guidelines, our research provides a granular analysis of how data volume, parameter size, and data construction methods influence the development of each underlying ability of LLM, such as creative writing, code generation, and logical reasoning. We present a meticulously curated dataset with over 40k instances across ten abilities and examine instruction-tuned models with 7b to 33b parameters. Our study reveals three primary findings: (i) Despite the models'' overall performance being tied to data and parameter scale, individual abilities have different sensitivities to these factors. (ii) Human-curated data strongly outperforms synthetic data from GPT-4 in efficiency and can constantly enhance model performance with volume increases, but is unachievable with synthetic data. (iii) Instruction data brings powerful cross-ability generalization, as evidenced by out-of-domain evaluations. Furthermore, we demonstrate how these findings can guide more efficient data constructions, leading to practical performance improvements on two public benchmarks.'
