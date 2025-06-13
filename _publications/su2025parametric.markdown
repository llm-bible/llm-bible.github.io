---
layout: publication
title: 'Parametric Retrieval Augmented Generation'
authors: Weihang Su, Yichen Tang, Qingyao Ai, Junxi Yan, Changyue Wang, Hongning Wang, Ziyi Ye, Yujia Zhou, Yiqun Liu
conference: "Arxiv"
year: 2025
bibkey: su2025parametric
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.15915"}
  - {name: "Code", url: "https://github.com/oneal2000/PRAG"}
tags: ['RAG', 'Has Code', 'Efficiency and Optimization']
---
Retrieval-augmented generation (RAG) techniques have emerged as a promising
solution to enhance the reliability of large language models (LLMs) by
addressing issues like hallucinations, outdated knowledge, and domain
adaptation. In particular, existing RAG methods append relevant documents
retrieved from external corpus or databases to the input of LLMs to guide their
generation process, which we refer to as the in-context knowledge injection
method. While this approach is simple and often effective, it has inherent
limitations. Firstly, increasing the context length and number of relevant
documents can lead to higher computational overhead and degraded performance,
especially in complex reasoning tasks. More importantly, in-context knowledge
injection operates primarily at the input level, but LLMs store their internal
knowledge in their parameters. This gap fundamentally limits the capacity of
in-context methods. To this end, we introduce Parametric retrieval-augmented
generation (Parametric RAG), a new RAG paradigm that integrates external
knowledge directly into the parameters of feed-forward networks (FFN) of an LLM
through document parameterization. This approach not only saves online
computational costs by eliminating the need to inject multiple documents into
the LLMs' input context, but also deepens the integration of external knowledge
into the parametric knowledge space of the LLM. Experimental results
demonstrate that Parametric RAG substantially enhances both the effectiveness
and efficiency of knowledge augmentation in LLMs. Also, it can be combined with
in-context RAG methods to achieve even better performance.
  We have open-sourced all the code, data, and models in the following
anonymized GitHub link: https://github.com/oneal2000/PRAG
