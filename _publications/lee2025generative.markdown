---
layout: publication
title: 'GRAM: Generative Recommendation Via Semantic-aware Multi-granular Late Fusion'
authors: Sunkyung Lee, Minjin Choi, Eunseong Choi, Hye-young Kim, Jongwuk Lee
conference: "Arxiv"
year: 2025
bibkey: lee2025generative
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.01673"}
  - {name: "Code", url: "https://github.com/skleee/GRAM"}
tags: ['Language Modeling', 'Merging', 'RAG', 'Has Code', 'Prompting', 'Applications']
---
Generative recommendation is an emerging paradigm that leverages the extensive knowledge of large language models by formulating recommendations into a text-to-text generation task. However, existing studies face two key limitations in (i) incorporating implicit item relationships and (ii) utilizing rich yet lengthy item information. To address these challenges, we propose a Generative Recommender via semantic-Aware Multi-granular late fusion (GRAM), introducing two synergistic innovations. First, we design semantic-to-lexical translation to encode implicit hierarchical and collaborative item relationships into the vocabulary space of LLMs. Second, we present multi-granular late fusion to integrate rich semantics efficiently with minimal information loss. It employs separate encoders for multi-granular prompts, delaying the fusion until the decoding stage. Experiments on four benchmark datasets show that GRAM outperforms eight state-of-the-art generative recommendation models, achieving significant improvements of 11.5-16.0% in Recall@5 and 5.3-13.6% in NDCG@5. The source code is available at https://github.com/skleee/GRAM.
