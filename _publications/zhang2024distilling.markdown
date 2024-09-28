---
layout: publication
title: Distilling Implicit Multimodal Knowledge into LLMs for Zero-Resource Dialogue Generation
authors: Zhang Bo, Ma Hui, Ding Jian, Wang Jian, Xu Bo, Lin Hongfei
conference: "Arxiv"
year: 2024
bibkey: zhang2024distilling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.10121"}
tags: ['ARXIV', 'Distillation', 'LLM', 'Merging', 'Model Architecture', 'RAG', 'Tools', 'Transformer']
---
Integrating multimodal knowledge into large language models (LLMs) represents a significant advancement in dialogue generation capabilities. However the effective incorporation of such knowledge in zero-resource scenarios remains a substantial challenge due to the scarcity of diverse high-quality dialogue datasets. To address this we propose the Visual Implicit Knowledge Distillation Framework (VIKDF) an innovative approach aimed at enhancing LLMs for enriched dialogue generation in zero-resource contexts by leveraging implicit multimodal knowledge. VIKDF comprises two main stages knowledge distillation using an Implicit Query Transformer to extract and encode visual implicit knowledge from image-text pairs into knowledge vectors; and knowledge integration employing a novel Bidirectional Variational Information Fusion technique to seamlessly integrate these distilled vectors into LLMs. This enables the LLMs to generate dialogues that are not only coherent and engaging but also exhibit a deep understanding of the context through implicit multimodal cues effectively overcoming the limitations of zero-resource scenarios. Our extensive experimentation across two dialogue datasets shows that VIKDF outperforms existing state-of-the-art models in generating high-quality dialogues. The code will be publicly available following acceptance.
