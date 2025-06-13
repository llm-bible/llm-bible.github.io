---
layout: publication
title: 'Nestools: A Dataset For Evaluating Nested Tool Learning Abilities Of Large Language Models'
authors: Han Han, Tong Zhu, Xiang Zhang, Mengsong Wu, Hao Xiong, Wenliang Chen
conference: "Arxiv"
year: 2024
bibkey: han2024dataset
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.11805"}
tags: ['Applications', 'Survey Paper', 'Tools', 'Reinforcement Learning']
---
Large language models (LLMs) combined with tool learning have gained
impressive results in real-world applications. During tool learning, LLMs may
call multiple tools in nested orders, where the latter tool call may take the
former response as its input parameters. However, current research on the
nested tool learning capabilities is still under-explored, since the existing
benchmarks lack relevant data instances. To address this problem, we introduce
NesTools to bridge the current gap in comprehensive nested tool learning
evaluations. NesTools comprises a novel automatic data generation method to
construct large-scale nested tool calls with different nesting structures. With
manual review and refinement, the dataset is in high quality and closely
aligned with real-world scenarios. Therefore, NesTools can serve as a new
benchmark to evaluate the nested tool learning abilities of LLMs. We conduct
extensive experiments on 22 LLMs, and provide in-depth analyses with NesTools,
which shows that current LLMs still suffer from the complex nested tool
learning task.
