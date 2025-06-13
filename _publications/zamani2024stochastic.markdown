---
layout: publication
title: 'Stochastic RAG: End-to-end Retrieval-augmented Generation Through Expected Utility Maximization'
authors: Hamed Zamani, Michael Bendersky
conference: "Arxiv"
year: 2024
bibkey: zamani2024stochastic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.02816"}
tags: ['RAG', 'Applications', 'Efficiency and Optimization']
---
This paper introduces Stochastic RAG--a novel approach for end-to-end
optimization of retrieval-augmented generation (RAG) models that relaxes the
simplifying assumptions of marginalization and document independence, made in
most prior work. Stochastic RAG casts the retrieval process in RAG as a
stochastic sampling without replacement process. Through this formulation, we
employ straight-through Gumbel-top-k that provides a differentiable
approximation for sampling without replacement and enables effective end-to-end
optimization for RAG. We conduct extensive experiments on seven diverse
datasets on a wide range of tasks, from open-domain question answering to fact
verification to slot-filling for relation extraction and to dialogue systems.
By applying this optimization method to a recent and effective RAG model, we
advance state-of-the-art results on six out of seven datasets.
