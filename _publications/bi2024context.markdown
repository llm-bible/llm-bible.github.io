---
layout: publication
title: 'Context-dpo: Aligning Language Models For Context-faithfulness'
authors: Baolong Bi, Shaohan Huang, Yiwei Wang, Tianchi Yang, Zihan Zhang, Haizhen Huang, Lingrui Mei, Junfeng Fang, Zehao Li, Furu Wei, Weiwei Deng, Feng Sun, Qi Zhang, Shenghua Liu
conference: "Arxiv"
year: 2024
bibkey: bi2024context
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.15280"}
  - {name: "Code", url: "https://github.com/byronBBL/Context-DPO"}
tags: ['RAG', 'Has Code', 'Efficiency and Optimization', 'Reinforcement Learning']
---
Reliable responses from large language models (LLMs) require adherence to
user instructions and retrieved information. While alignment techniques help
LLMs align with human intentions and values, improving context-faithfulness
through alignment remains underexplored. To address this, we propose
\\(\textbf\{Context-DPO\}\\), the first alignment method specifically designed to
enhance LLMs' context-faithfulness. We introduce \\(\textbf\{ConFiQA\}\\), a
benchmark that simulates Retrieval-Augmented Generation (RAG) scenarios with
knowledge conflicts to evaluate context-faithfulness. By leveraging faithful
and stubborn responses to questions with provided context from ConFiQA, our
Context-DPO aligns LLMs through direct preference optimization. Extensive
experiments demonstrate that our Context-DPO significantly improves
context-faithfulness, achieving 35% to 280% improvements on popular open-source
models. Further analysis demonstrates that Context-DPO preserves LLMs'
generative capabilities while providing interpretable insights into context
utilization. Our code and data are released at
https://github.com/byronBBL/Context-DPO
