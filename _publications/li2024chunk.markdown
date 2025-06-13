---
layout: publication
title: 'Chunk-distilled Language Modeling'
authors: Yanhong Li, Karen Livescu, Jiawei Zhou
conference: "Arxiv"
year: 2024
bibkey: li2024chunk
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.00343'}
tags: ['Language Modeling', 'RAG', 'Efficiency and Optimization', 'Training Techniques', 'Tools']
---
We introduce Chunk-Distilled Language Modeling (CD-LM), an approach to text
generation that addresses two challenges in current large language models
(LLMs): the inefficiency of token-level generation, and the difficulty of
adapting to new data and knowledge. Our method combines deep network-based LLMs
with a straightforward retrieval module, which allows the generation of
multi-token text chunks at a single decoding step. Our retrieval framework
enables flexible construction of model- or domain-specific datastores, either
leveraging the internal knowledge of existing models, or incorporating expert
insights from human-annotated corpora. This adaptability allows for enhanced
control over the language model's distribution without necessitating additional
training. We present the CD-LM formulation along with performance metrics
demonstrating its ability to improve language model performance and efficiency
across a diverse set of downstream tasks. Code and data will be made publicly
available.
