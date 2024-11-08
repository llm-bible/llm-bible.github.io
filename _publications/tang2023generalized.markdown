---
layout: publication
title: 'Toolalpaca: Generalized Tool Learning For Language Models With 3000 Simulated Cases'
authors: Tang Qiaoyu, Deng Ziliang, Lin Hongyu, Han Xianpei, Liang Qiao, Cao Boxi, Sun Le
conference: "Arxiv"
year: 2023
bibkey: tang2023generalized
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.05301"}
tags: ['Agentic', 'GPT', 'Model Architecture', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Enabling large language models to utilize real-world tools effectively is
crucial for achieving embodied intelligence. Existing approaches to tool
learning have either primarily relied on extremely large language models, such
as GPT-4, to attain generalized tool-use abilities in a zero-shot manner, or
utilized supervised learning to train limited scopes of tools on compact
models. However, it remains uncertain whether smaller language models can
achieve generalized tool-use abilities without tool-specific training. To
address this question, this paper introduces ToolAlpaca, a novel framework
designed to automatically generate a diverse tool-use corpus and learn
generalized tool-use abilities on compact language models with minimal human
intervention. Specifically, ToolAlpaca first automatically creates a highly
diversified tool-use corpus by building a multi-agent simulation environment.
The corpus contains 3938 tool-use instances from more than 400 real-world tool
APIs spanning 50 distinct categories. Subsequently, the constructed corpus is
employed to fine-tune compact language models, resulting in two models, namely
ToolAlpaca-7B and ToolAlpaca-13B, respectively. Finally, we evaluate the
ability of these models to utilize previously unseen tools without specific
training. Experimental results demonstrate that ToolAlpaca achieves effective
generalized tool-use capabilities comparable to those of extremely large
language models like GPT-3.5, demonstrating that learning generalized tool-use
ability is feasible for compact language models.
