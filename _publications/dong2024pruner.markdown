---
layout: publication
title: Pruner45;zero Evolving Symbolic Pruning Metric From Scratch For Large Language Models
authors: Dong Peijie, Li Lujun, Tang Zhenheng, Liu Xiang, Pan Xinglin, Wang Qiang, Chu Xiaowen
conference: "Arxiv"
year: 2024
bibkey: dong2024pruner
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.02924"}
  - {name: "Code", url: "https://github.com/pprp/Pruner&#45;Zero&#125;"}
tags: ['Efficiency And Optimization', 'Has Code', 'Language Modeling', 'Pruning', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Despite the remarkable capabilities Large Language Models (LLMs) face deployment challenges due to their extensive size. Pruning methods drop a subset of weights to accelerate but many of them require retraining which is prohibitively expensive and computationally demanding. Recently post45;training pruning approaches introduced novel metrics enabling the pruning of LLMs without retraining. However these metrics require the involvement of human experts and tedious trial and error. To efficiently identify superior pruning metrics we develop an automatic framework for searching symbolic pruning metrics using genetic programming. In particular we devise an elaborate search space encompassing the existing pruning metrics to discover the potential symbolic pruning metric. We propose an opposing operation simplification strategy to increase the diversity of the population. In this way Pruner45;Zero allows auto45;generation of symbolic pruning metrics. Based on the searched results we explore the correlation between pruning metrics and performance after pruning and summarize some principles. Extensive experiments on LLaMA and LLaMA45;2 on language modeling and zero45;shot tasks demonstrate that our Pruner45;Zero obtains superior performance than SOTA post45;training pruning methods. Code at url123;https://github.com/pprp/Pruner&#45;Zero&#125;.
