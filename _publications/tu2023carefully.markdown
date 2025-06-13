---
layout: publication
title: 'Chatlog: Carefully Evaluating The Evolution Of Chatgpt Across Time'
authors: Shangqing Tu, Chunyang Li, Jifan Yu, Xiaozhi Wang, Lei Hou, Juanzi Li
conference: "Arxiv"
year: 2023
bibkey: tu2023carefully
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2304.14106"}
  - {name: "Code", url: "https://github.com/THU-KEG/ChatLog/"}
tags: ['Security', 'Model Architecture', 'Reinforcement Learning', 'GPT', 'Has Code']
---
ChatGPT has achieved great success and can be considered to have acquired an
infrastructural status. There are abundant works for evaluating ChatGPT on
benchmarks. However, existing benchmarks encounter two challenges: (1)
Disregard for periodical evaluation and (2) Lack of fine-grained features. In
this paper, we construct ChatLog, an ever-updating dataset with large-scale
records of diverse long-form ChatGPT responses for 21 NLP benchmarks from
March, 2023 to now. We conduct a comprehensive performance evaluation to find
that most capabilities of ChatGPT improve over time except for some abilities,
and there exists a step-wise evolving pattern of ChatGPT. We further analyze
the inherent characteristics of ChatGPT by extracting the knowledge and
linguistic features. We find some stable features that stay unchanged and apply
them on the detection of ChatGPT-generated texts to improve the robustness of
cross-version detection. We will continuously maintain our project at
\url\{https://github.com/THU-KEG/ChatLog/\}.
