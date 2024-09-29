---
layout: publication
title: RAT Retrieval Augmented Thoughts Elicit Context45;aware Reasoning In Long45;horizon Generation
authors: Wang Zihao, Liu Anji, Lin Haowei, Li Jiaqi, Ma Xiaojian, Liang Yitao
conference: "Arxiv"
year: 2024
bibkey: wang2024retrieval
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.05313"}
  - {name: "Code", url: "https://craftjarvis.github.io/RAT"}
tags: ['Applications', 'GPT', 'Has Code', 'Model Architecture', 'RAG']
---
We explore how iterative revising a chain of thoughts with the help of information retrieval significantly improves large language models reasoning and generation ability in long45;horizon generation tasks while hugely mitigating hallucination. In particular the proposed method 45;45; retrieval45;augmented thoughts (RAT) 45;45; revises each thought step one by one with retrieved information relevant to the task query the current and the past thought steps after the initial zero45;shot CoT is generated. Applying RAT to GPT45;3.5 GPT45;4 and CodeLLaMA45;7b substantially improves their performances on various long45;horizon generation tasks; on average of relatively increasing rating scores by 13.6337; on code generation 16.9637; on mathematical reasoning 19.237; on creative writing and 42.7837; on embodied task planning. The demo page can be found at https://craftjarvis.github.io/RAT
