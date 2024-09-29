---
layout: publication
title: Graph Chain-of-thought\: Augmenting Large Language Models By Reasoning On Graphs
authors: Jin Bowen, Xie Chulin, Zhang Jiawei, Roy Kashob Kumar, Zhang Yu, Li Zheng, Li Ruirui, Tang Xianfeng, Wang Suhang, Meng Yu, Han Jiawei
conference: "Arxiv"
year: 2024
bibkey: jin2024graph
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.07103"}
  - {name: "Code", url: "https://github.com/PeterGriffinJin/Graph-CoT"}
tags: ['Has Code', 'Pretraining Methods', 'RAG', 'Tools']
---
Large language models (LLMs) while exhibiting exceptional performance suffer from hallucinations especially on knowledge-intensive tasks. Existing works propose to augment LLMs with individual text units retrieved from external knowledge corpora to alleviate the issue. However in many domains texts are interconnected (e.g. academic papers in a bibliographic graph are linked by citations and co-authorships) which form a (text-attributed) graph. The knowledge in such graphs is encoded not only in single texts/nodes but also in their associated connections. To facilitate the research of augmenting LLMs with graphs we manually construct a Graph Reasoning Benchmark dataset called GRBench containing 1740 questions that can be answered with the knowledge from 10 domain graphs. Then we propose a simple and effective framework called Graph Chain-of-thought (Graph-CoT) to augment LLMs with graphs by encouraging LLMs to reason on the graph iteratively. Each Graph-CoT iteration consists of three sub-steps LLM reasoning LLM-graph interaction and graph execution. We conduct systematic experiments with three LLM backbones on GRBench where Graph-CoT outperforms the baselines consistently. The code is available at https://github.com/PeterGriffinJin/Graph-CoT."
