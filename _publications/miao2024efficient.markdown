---
layout: publication
title: 'An Efficient Inference Framework For Early-exit Large Language Models'
authors: Miao Ruijie, Yan Yihan, Yao Xinshuo, Yang Tong
conference: "Arxiv"
year: 2024
bibkey: miao2024efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.20272"}
tags: ['Efficiency And Optimization', 'Reinforcement Learning', 'Tools', 'Uncategorized']
---
Building efficient inference framework has gained increasing interests for research community. Early-exit models, a variant of LLMs, improves the inference efficiency of LLMs by skipping rest layers and directly generate output tokens when they are confident enough. However, there is no work of LLM inference framework that takes early-exit models into consideration. This is non-trivial as prior art on LLM inference cannot be directly applied to early-exit models. In this work, we solves two key challenges in building efficient inference framework for early-exit models: (1) batch inference at iteration-level granularity; and (2) KV cache management. For the former, we propose to process the batch until all sequences surpass the early-exit confidence threshold. For the latter, we propose to fill the KV cache of rest layers before the iteration terminates. Our evaluation shows that, compared with the original vLLM operating at full layers, our solution achieves up to 1.25x speed up.
