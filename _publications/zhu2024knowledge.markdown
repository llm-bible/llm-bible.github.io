---
layout: publication
title: Knowagent\: Knowledge-augmented Planning For Llm-based Agents
authors: Zhu Yuqi, Qiao Shuofei, Ou Yixin, Deng Shumin, Zhang Ningyu, Lyu Shiwei, Shen Yue, Liang Lei, Gu Jinjie, Chen Huajun
conference: "Arxiv"
year: 2024
bibkey: zhu2024knowledge
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.03101"}
  - {name: "Code", url: "https://github.com/zjunlp/KnowAgent"}
tags: ['Agentic', 'Has Code', 'Reinforcement Learning']
---
Large Language Models (LLMs) have demonstrated great potential in complex reasoning tasks yet they fall short when tackling more sophisticated challenges especially when interacting with environments through generating executable actions. This inadequacy primarily stems from the lack of built-in action knowledge in language agents which fails to effectively guide the planning trajectories during task solving and results in planning hallucination. To address this issue we introduce KnowAgent a novel approach designed to enhance the planning capabilities of LLMs by incorporating explicit action knowledge. Specifically KnowAgent employs an action knowledge base and a knowledgeable self-learning strategy to constrain the action path during planning enabling more reasonable trajectory synthesis and thereby enhancing the planning performance of language agents. Experimental results on HotpotQA and ALFWorld based on various backbone models demonstrate that KnowAgent can achieve comparable or superior performance to existing baselines. Further analysis indicates the effectiveness of KnowAgent in terms of planning hallucinations mitigation. Code is available in https://github.com/zjunlp/KnowAgent."
