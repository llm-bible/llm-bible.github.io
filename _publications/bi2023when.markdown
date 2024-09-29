---
layout: publication
title: When Do Program45;of45;thoughts Work For Reasoning
authors: Bi Zhen, Zhang Ningyu, Jiang Yinuo, Deng Shumin, Zheng Guozhou, Chen Huajun
conference: "Arxiv"
year: 2023
bibkey: bi2023when
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.15452"}
  - {name: "Code", url: "https://github.com/zjunlp/EasyInstruct"}
tags: ['Applications', 'Has Code', 'Prompting', 'Tools']
---
In the realm of embodied artificial intelligence the reasoning capabilities of Large Language Models (LLMs) play a pivotal role. Although there are effective methods like program45;of45;thought prompting for LLMs which uses programming language to tackle complex reasoning tasks the specific impact of code data on the improvement of reasoning capabilities remains under45;explored. To address this gap we propose complexity45;impacted reasoning score (CIRS) which combines structural and logical attributes to measure the correlation between code and reasoning abilities. Specifically we use the abstract syntax tree to encode the structural information and calculate logical complexity by considering the difficulty and the cyclomatic complexity. Through an empirical analysis we find not all code data of complexity can be learned or understood by LLMs. Optimal level of complexity is critical to the improvement of reasoning abilities by program45;aided prompting. Then we design an auto45;synthesizing and stratifying algorithm and apply it to instruction generation for mathematical reasoning and code data filtering for code generation tasks. Extensive results demonstrates the effectiveness of our proposed approach. Code will be integrated into the EasyInstruct framework at https://github.com/zjunlp/EasyInstruct.
