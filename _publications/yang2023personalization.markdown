---
layout: publication
title: 'PALR: Personalization Aware Llms For Recommendation'
authors: Fan Yang, Zheng Chen, Ziyan Jiang, Eunah Cho, Xiaojiang Huang, Yanbin Lu
conference: "Arxiv"
year: 2023
bibkey: yang2023personalization
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.07622"}
tags: ['Training Techniques', 'Model Architecture', 'Few-Shot', 'Tools', 'RAG', 'RecSys', 'Attention Mechanism']
---
Large language models (LLMs) have recently received significant attention for
their exceptional capabilities. Despite extensive efforts in developing
general-purpose LLMs that can be utilized in various natural language
processing (NLP) tasks, there has been less research exploring their potential
in recommender systems. In this paper, we propose a novel framework, named
PALR, which aiming to combine user history behaviors (such as clicks,
purchases, ratings, etc.) with LLMs to generate user preferred items.
Specifically, we first use user/item interactions as guidance for candidate
retrieval. Then we adopt a LLM-based ranking model to generate recommended
items. Unlike existing approaches that typically adopt general-purpose LLMs for
zero/few-shot recommendation testing or training on small-sized language models
(with less than 1 billion parameters), which cannot fully elicit LLMs'
reasoning abilities and leverage rich item side parametric knowledge, we
fine-tune a 7 billion parameters LLM for the ranking purpose. This model takes
retrieval candidates in natural language format as input, with instruction
which explicitly asking to select results from input candidates during
inference. Our experimental results demonstrate that our solution outperforms
state-of-the-art models on various sequential recommendation tasks.
