---
layout: publication
title: Enhancing Retrieval45;augmented Large Language Models With Iterative Retrieval45;generation Synergy
authors: Shao Zhihong, Gong Yeyun, Shen Yelong, Huang Minlie, Duan Nan, Chen Weizhu
conference: "Arxiv"
year: 2023
bibkey: shao2023enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.15294"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture', 'RAG', 'Reinforcement Learning']
---
Large language models are powerful text processors and reasoners but are still subject to limitations including outdated knowledge and hallucinations which necessitates connecting them to the world. Retrieval45;augmented large language models have raised extensive attention for grounding model generation on external knowledge. However retrievers struggle to capture relevance especially for queries with complex information needs. Recent work has proposed to improve relevance modeling by having large language models actively involved in retrieval i.e. to improve retrieval with generation. In this paper we show that strong performance can be achieved by a method we call Iter45;RetGen which synergizes retrieval and generation in an iterative manner. A model output shows what might be needed to finish a task and thus provides an informative context for retrieving more relevant knowledge which in turn helps generate a better output in the next iteration. Compared with recent work which interleaves retrieval with generation when producing an output Iter45;RetGen processes all retrieved knowledge as a whole and largely preserves the flexibility in generation without structural constraints. We evaluate Iter45;RetGen on multi45;hop question answering fact verification and commonsense reasoning and show that it can flexibly leverage parametric knowledge and non45;parametric knowledge and is superior to or competitive with state45;of45;the45;art retrieval45;augmented baselines while causing fewer overheads of retrieval and generation. We can further improve performance via generation45;augmented retrieval adaptation.
