---
layout: publication
title: Cross45;task Defense Instruction45;tuning Llms For Content Safety
authors: Fu Yu, Xiao Wen, Chen Jia, Li Jiachen, Papalexakis Evangelos, Chien Aichi, Dong Yue
conference: "Arxiv"
year: 2024
bibkey: fu2024cross
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.15202"}
tags: ['Applications', 'Reinforcement Learning', 'Responsible AI']
---
Recent studies reveal that Large Language Models (LLMs) face challenges in balancing safety with utility particularly when processing long texts for NLP tasks like summarization and translation. Despite defenses against malicious short questions the ability of LLMs to safely handle dangerous long content such as manuals teaching illicit activities remains unclear. Our work aims to develop robust defenses for LLMs in processing malicious documents alongside benign NLP task queries. We introduce a defense dataset comprised of safety45;related examples and propose single45;task and mixed45;task losses for instruction tuning. Our empirical results demonstrate that LLMs can significantly enhance their capacity to safely manage dangerous content with appropriate instruction tuning. Additionally strengthening the defenses of tasks most susceptible to misuse is effective in protecting LLMs against processing harmful information. We also observe that trade45;offs between utility and safety exist in defense strategies where Llama2 utilizing our proposed approach displays a significantly better balance compared to Llama1.
