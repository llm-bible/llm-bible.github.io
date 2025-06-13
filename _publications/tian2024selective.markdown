---
layout: publication
title: 'Selective Prompt Anchoring For Code Generation'
authors: Yuan Tian, Tianyi Zhang
conference: "Arxiv"
year: 2024
bibkey: tian2024selective
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.09121"}
  - {name: "Code", url: "https://github.com/magic-YuanTian/Selective-Prompt-Anchoring"}
tags: ['Model Architecture', 'Has Code', 'Prompting', 'Applications', 'Attention Mechanism']
---
Recent advances in large language models (LLMs) have transformed software
development by automatically generating code from natural language. Yet
challenges remain in generating fully correct code that aligns with user
intent. Our study reveals that LLMs tend to pay less attention to user prompts
as more code tokens are generated. We hypothesize that this attention dilution
issue is an important reason for code generation errors. To mitigate this
issue, we propose Selective Prompt Anchoring (SPA) to guide code LLMs to pay
more attention to user intent when generating code. We evaluate SPA using six
base LLMs across six benchmarks. Our results demonstrate that SPA enhances
Pass@1 by up to 12.9%, consistently outperforming SOTA code generation methods
in all settings. Our code is available at
https://github.com/magic-YuanTian/Selective-Prompt-Anchoring.
