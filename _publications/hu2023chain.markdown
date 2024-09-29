---
layout: publication
title: "Chain-of-symbol Prompting Elicits Planning In Large Langauge Models"
authors: Hu Hanxu, Lu Hongyuan, Zhang Huajian, Song Yun-ze, Lam Wai, Zhang Yue
conference: "Arxiv"
year: 2023
bibkey: hu2023chain
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.10276"}
  - {name: "Code", url: "https://github.com/hanxuhu/chain-of-symbol-planning"}
tags: ['GPT', 'Has Code', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
In this paper we take the initiative to investigate the performance of LLMs on complex planning tasks that require LLMs to understand a virtual spatial environment simulated via natural language and act correspondingly in text. We propose a benchmark named Natural Language Planning and Action (Natala) composed of a set of novel tasks Brick World NLVR-based Manipulations and Natural Language Navigation. We found that current popular LLMs such as ChatGPT still lack abilities in complex planning. This arises a question -- do the LLMs have a good understanding of the environments described in natural language or maybe other alternatives such as symbolic representations are neater and hence better to be understood by LLMs To this end we propose a novel method called CoS (Chain-of-Symbol Prompting) that represents the complex environments with condensed symbolic spatial representations during the chained intermediate thinking steps. CoS is easy to use and does not need additional training on LLMs. Extensive experiments indicate that CoS clearly surpasses the performance of the Chain-of-Thought (CoT) Prompting in all three planning tasks with even fewer tokens used in the inputs compared with CoT on ChatGPT and InstructGPT. The performance gain is strong by up to 60.837; accuracy (from 31.837; to 92.637;) on Brick World for ChatGPT. CoS also reduces the number of tokens in the prompt obviously by up to 65.837; of the tokens (from 407 to 139) for the intermediate steps from demonstrations on Brick World. Code and data available at https://github.com/hanxuhu/chain-of-symbol-planning"
