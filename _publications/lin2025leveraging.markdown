---
layout: publication
title: 'Leveraging Constrained Monte Carlo Tree Search To Generate Reliable Long Chain-of-thought For Mathematical Reasoning'
authors: Qingwen Lin, Boyan Xu, Zijian Li, Zhifeng Hao, Keli Zhang, Ruichu Cai
conference: "Arxiv"
year: 2025
bibkey: lin2025leveraging
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.11169'}
tags: ['Attention Mechanism', 'RAG', 'Model Architecture', 'Tools', 'Training Techniques', 'Prompting', 'Reinforcement Learning']
---
Recently, Long Chain-of-Thoughts (CoTs) have gained widespread attention for
improving the reasoning capabilities of Large Language Models (LLMs). This
necessitates that existing LLMs, which lack the ability to generate Long CoTs,
to acquire such capability through post-training methods. Without additional
training, LLMs typically enhance their mathematical reasoning abilities through
inference scaling methods such as MCTS. However, they are hindered by the large
action space and inefficient search strategies, making it challenging to
generate Long CoTs effectively. To tackle this issue, we propose constraining
the action space and guiding the emergence of Long CoTs through a refined
search strategy. In our proposed Constrained Monte Carlo Tree Search (C-MCTS)
framework, we limit the actions selected from a constrained action space, which
is divided into five disjoint subsets: *understanding*, *planning*,
*reflection*, *coding*, and *summary*. Each subset is further
constrained to a small number of predefined prompts, rather than allowing LLMs
to generate actions arbitrarily. Additionally, we refine the search strategy by
incorporating prior knowledge about the action sets, such as a human-like
partial order of the action subsets and the pretrained process reward models.
These strategies work together to significantly reduce the vast search space of
Long CoTs. Extensive evaluations on mathematical reasoning benchmarks show
that, under zero-shot settings, our method enables the 7B model to achieve
reasoning capabilities that surpass those of the 72B model.
