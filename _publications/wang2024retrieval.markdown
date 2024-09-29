---
layout: publication
title: 'RAT: Retrieval Augmented Thoughts Elicit Context-aware Reasoning In Long-horizon Generation'
authors: Wang Zihao, Liu Anji, Lin Haowei, Li Jiaqi, Ma Xiaojian, Liang Yitao
conference: "Arxiv"
year: 2024
bibkey: wang2024retrieval
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.05313"}
  - {name: "Code", url: "https://craftjarvis.github.io/RAT"}
tags: ['Applications', 'GPT', 'Has Code', 'Model Architecture', 'RAG']
---
We explore how iterative revising a chain of thoughts with the help of information retrieval significantly improves large language models reasoning and generation ability in long-horizon generation tasks while hugely mitigating hallucination. In particular the proposed method -- retrieval-augmented thoughts (RAT) -- revises each thought step one by one with retrieved information relevant to the task query the current and the past thought steps after the initial zero-shot CoT is generated. Applying RAT to GPT-3.5 GPT-4 and CodeLLaMA-7b substantially improves their performances on various long-horizon generation tasks; on average of relatively increasing rating scores by 13.6337; on code generation 16.9637; on mathematical reasoning 19.237; on creative writing and 42.7837; on embodied task planning. The demo page can be found at https://craftjarvis.github.io/RAT"
