---
layout: publication
title: Aqa-bench An Interactive Benchmark For Evaluating Llms Sequential Reasoning Ability
authors: Yang Siwei, Zhao Bingchen, Xie Cihang
conference: "Arxiv"
year: 2024
bibkey: yang2024aqa
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.09404"}
  - {name: "Code", url: "https://github.com/UCSC-VLAA/AQA-Bench"}
tags: ['Few Shot', 'GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods']
---
This paper introduces AQA-Bench a novel benchmark to assess the sequential reasoning capabilities of large language models (LLMs) in algorithmic contexts such as depth-first search (DFS). The key feature of our evaluation benchmark lies in its interactive evaluation protocol -- for example in DFS the availability of each nodes connected edge is contingent upon the models traversal to that node thereby necessitating the LLMs ability to effectively remember visited nodes and strategize subsequent moves. We comprehensively build AQA-Bench with three different algorithms namely binary search depth-first search and breadth-first search and to evaluate the sequential reasoning ability of 12 different LLMs. Our investigations reveal several interesting findings (1) Closed-source models like GPT-4 and Gemini generally show strong sequential reasoning ability significantly outperforming open-source LLMs. (2) Naively providing interactive examples may inadvertently hurt few-shot performance. (3) A very limited number of predecessor steps following the optimal policy can substantially boost small models performance. (4) The scaling correlation between performance and model size is not always significant sometimes even showcasing an inverse trend. We hope our study can catalyze future work on advancing the understanding and enhancement of LLMs capabilities in sequential reasoning. The code is available at https://github.com/UCSC-VLAA/AQA-Bench."
