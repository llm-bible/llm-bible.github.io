---
layout: publication
title: Vtrain A Simulation Framework For Evaluating Cost-effective And Compute-optimal Large Language Model Training
authors: Bang Jehyeon, Choi Yujeong, Kim Myeongwoo, Kim Yongdeok, Rhu Minsoo
conference: "Arxiv"
year: 2023
bibkey: bang2023simulation
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.12391"}
tags: ['Large Scale Training', 'Model Architecture', 'Pretraining Methods', 'Tools', 'Training Techniques']
---
As large language models (LLMs) become widespread in various application domains a critical challenge the AI community is facing is how to train these large AI models in a cost-effective manner. Existing LLM training plans typically employ a heuristic based parallel training strategy which is based on empirical observations rather than grounded upon a thorough examination of the search space of LLM parallelization. Such limitation renders existing systems to leave significant performance left on the table wasting millions of dollars worth of training cost. This paper presents our profiling-driven simulator called vTrain providing AI practitioners a fast yet accurate software framework to determine an efficient and cost-effective LLM training system configuration. We demonstrate vTrains practicality through several case studies e.g. effectively evaluating optimal training parallelization strategies that balances training time and its associated training cost efficient multi-tenant GPU cluster schedulers targeting multiple LLM training jobs and determining a compute-optimal LLM model architecture given a fixed compute budget.
