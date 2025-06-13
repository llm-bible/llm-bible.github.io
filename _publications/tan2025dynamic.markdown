---
layout: publication
title: 'Dynamic Parametric Retrieval Augmented Generation For Test-time Knowledge Enhancement'
authors: Yuqiao Tan, Shizhu He, Huanxuan Liao, Jun Zhao, Kang Liu
conference: "Arxiv"
year: 2025
bibkey: tan2025dynamic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.23895"}
  - {name: "Code", url: "https://github.com/Trae1ounG/DyPRAG"}
tags: ['Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG', 'Merging', 'Has Code', 'Applications']
---
Retrieval-augmented generation (RAG) enhances large language models (LLMs) by
retrieving relevant documents from external sources and incorporating them into
the context. While it improves reliability by providing factual texts, it
significantly increases inference costs as context length grows and introduces
challenging issue of RAG hallucination, primarily caused by the lack of
corresponding parametric knowledge in LLMs. An efficient solution is to enhance
the knowledge of LLMs at test-time. Parametric RAG (PRAG) addresses this by
embedding document into LLMs parameters to perform test-time knowledge
enhancement, effectively reducing inference costs through offline training.
However, its high training and storage costs, along with limited generalization
ability, significantly restrict its practical adoption. To address these
challenges, we propose Dynamic Parametric RAG (DyPRAG), a novel framework that
leverages a lightweight parameter translator model to efficiently convert
documents into parametric knowledge. DyPRAG not only reduces inference,
training, and storage costs but also dynamically generates parametric
knowledge, seamlessly enhancing the knowledge of LLMs and resolving knowledge
conflicts in a plug-and-play manner at test-time. Extensive experiments on
multiple datasets demonstrate the effectiveness and generalization capabilities
of DyPRAG, offering a powerful and practical RAG paradigm which enables
superior knowledge fusion and mitigates RAG hallucination in real-world
applications. Our code is available at https://github.com/Trae1ounG/DyPRAG.
