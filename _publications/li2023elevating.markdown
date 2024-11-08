---
layout: publication
title: 'Motcoder: Elevating Large Language Models With Modular Of Thought For Challenging Programming Tasks'
authors: Li Jingyao, Chen Pengguang, Xia Bin, Xu Hong, Jia Jiaya
conference: "Arxiv"
year: 2023
bibkey: li2023elevating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.15960"}
  - {name: "Code", url: "https://github.com/dvlab-research/MoTCoder"}
tags: ['Has Code', 'Tools']
---
Large Language Models (LLMs) have showcased impressive capabilities in
handling straightforward programming tasks. However, their performance tends to
falter when confronted with more challenging programming problems. We observe
that conventional models often generate solutions as monolithic code blocks,
restricting their effectiveness in tackling intricate questions. To overcome
this limitation, we present Modular-of-Thought Coder (MoTCoder). We introduce a
pioneering framework for MoT instruction tuning, designed to promote the
decomposition of tasks into logical sub-tasks and sub-modules. Our
investigations reveal that, through the cultivation and utilization of
sub-modules, MoTCoder significantly improves both the modularity and
correctness of the generated solutions, leading to substantial relative pass@1
improvements of 12.9% on APPS and 9.43% on CodeContests. Our codes are
available at https://github.com/dvlab-research/MoTCoder.
