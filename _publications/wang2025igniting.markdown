---
layout: publication
title: 'Stepsearch: Igniting Llms Search Ability Via Step-wise Proximal Policy Optimization'
authors: Ziliang Wang, Xuhui Zheng, Kang An, Cijun Ouyang, Jialu Cai, Yuhang Wang, Yichao Wu
conference: "Arxiv"
year: 2025
bibkey: wang2025igniting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.15107"}
  - {name: "Code", url: "https://github.com/Zillwang/StepSearch"}
tags: ['Agentic', 'Efficiency and Optimization', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'Has Code']
---
Efficient multi-hop reasoning requires Large Language Models (LLMs) based agents to acquire high-value external knowledge iteratively. Previous work has explored reinforcement learning (RL) to train LLMs to perform search-based document retrieval, achieving notable improvements in QA performance, but underperform on complex, multi-hop QA resulting from the sparse rewards from global signal only. To address this gap in existing research, we introduce StepSearch, a framework for search LLMs that trained with step-wise proximal policy optimization method. It consists of richer and more detailed intermediate search rewards and token-level process supervision based on information gain and redundancy penalties to better guide each search step. We constructed a fine-grained question-answering dataset containing sub-question-level search trajectories based on open source datasets through a set of data pipeline method. On standard multi-hop QA benchmarks, it significantly outperforms global-reward baselines, achieving 11.2% and 4.2% absolute improvements for 3B and 7B models over various search with RL baselines using only 19k training data, demonstrating the effectiveness of fine-grained, stepwise supervision in optimizing deep search LLMs. Our code will be released on https://github.com/Zillwang/StepSearch.
