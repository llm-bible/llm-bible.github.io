---
layout: publication
title: 'O1 Embedder: Let Retrievers Think Before Action'
authors: Ruiran Yan, Zheng Liu, Defu Lian
conference: "Arxiv"
year: 2025
bibkey: yan2025let
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.07555"}
tags: ['Pretraining Methods', 'Training Techniques']
---
The growing power of large language models (LLMs) has revolutionized how
people access and utilize information. Notably, the LLMs excel at performing
fine-grained data representation, which facilitates precise retrieval of
information. They also generate high-quality answers based on external
references, enabling the production of useful knowledge. The recent
introduction of reasoning models, like OpenAI O1 and DeepSeek R1, marks another
leap forward, highlighting LLMs' ability to think progressively before
delivering final answers. This breakthrough significantly improves the ability
to address complex tasks, e.g., coding and math proofs.
  Inspired by this progress, we aim to develop similar capabilities for
retrieval models, which hold great promise for tackling critical challenges in
the field, including multi-task retrieval, zero-shot retrieval, and tasks
requiring intensive reasoning of complex relationships. With this motivation,
we propose a novel approach called O1 Embedder, which generates useful thoughts
for the input query before making retrieval for the target documents. To
realize this objective, we conquer two technical difficulties. First, we design
a data synthesis workflow, creating training signals for O1 Embedder by
generating initial thoughts from an LLM-expert and subsequently refining them
using a retrieval committee. Second, we optimize the training process, enabling
a pre-trained model to be jointly fine-tuned to generate retrieval thoughts via
behavior cloning and perform dense retrieval through contrastive learning. Our
approach is evaluated by comprehensive experiments, where substantial
improvements are achieved across 12 popular datasets, spanning both in-domain
and out-of-domain scenarios. These results highlight O1 Embedder's remarkable
accuracy and generalizability, paving the way for the development of
next-generation IR foundation models.
