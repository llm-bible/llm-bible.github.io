---
layout: publication
title: Accelerating Inference In Large Language Models With A Unified Layer Skipping Strategy
authors: Liu Yijin, Meng Fandong, Zhou Jie
conference: "Arxiv"
year: 2024
bibkey: liu2024accelerating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.06954"}
tags: ['Applications', 'Reinforcement Learning']
---
Recently dynamic computation methods have shown notable acceleration for Large Language Models (LLMs) by skipping several layers of computations through elaborate heuristics or additional predictors. However in the decoding process of existing approaches different samples are assigned different computational budgets which cannot guarantee a stable and precise acceleration effect. Furthermore existing approaches generally skip multiple contiguous layers at the bottom or top of the layers leading to a drastic change in the models layer45;wise representations and thus a consequent performance degeneration. Therefore we propose a Unified Layer Skipping strategy which selects the number of layers to skip computation based solely on the target speedup ratio and then skips the corresponding number of intermediate layer computations in a balanced manner. Since the Unified Layer Skipping strategy is independent of input samples it naturally supports popular acceleration techniques such as batch decoding and KV caching thus demonstrating more practicality for real45;world applications. Experimental results on two common tasks i.e. machine translation and text summarization indicate that given a target speedup ratio the Unified Layer Skipping strategy significantly enhances both the inference performance and the actual model throughput over existing dynamic approaches.
