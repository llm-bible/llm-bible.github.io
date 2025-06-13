---
layout: publication
title: 'Unicorn: Unified Commented Retrieval Network With Lmms'
authors: Maximilian Jaritz, Matthieu Guillaumin, Sabine Sternig, Loris Bazzani
conference: "Arxiv"
year: 2025
bibkey: jaritz2025unified
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.08254"}
tags: ['Multimodal Models', 'Tools', 'Reinforcement Learning', 'Language Modeling', 'RAG', 'Applications']
---
Multimodal retrieval methods have limitations in handling complex,
compositional queries that require reasoning about the visual content of both
the query and the retrieved entities. On the other hand, Large Multimodal
Models (LMMs) can answer with language to more complex visual questions, but
without the inherent ability to retrieve relevant entities to support their
answers. We aim to address these limitations with UniCoRN, a Unified Commented
Retrieval Network that combines the strengths of composed multimodal retrieval
methods and generative language approaches, going beyond Retrieval-Augmented
Generation (RAG). We introduce an entity adapter module to inject the retrieved
multimodal entities back into the LMM, so it can attend to them while
generating answers and comments. By keeping the base LMM frozen, UniCoRN
preserves its original capabilities while being able to perform both retrieval
and text generation tasks under a single integrated framework. To assess these
new abilities, we introduce the Commented Retrieval task (CoR) and a
corresponding dataset, with the goal of retrieving an image that accurately
answers a given question and generate an additional textual response that
provides further clarification and details about the visual information. We
demonstrate the effectiveness of UniCoRN on several datasets showing
improvements of +4.5% recall over the state of the art for composed multimodal
retrieval and of +14.9% METEOR / +18.4% BEM over RAG for commenting in CoR.
