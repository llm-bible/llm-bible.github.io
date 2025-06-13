---
layout: publication
title: 'Constrained Reasoning Chains For Enhancing Theory-of-mind In Large Language Models'
authors: Zizheng Lin, Chunkit Chan, Yangqiu Song, Xin Liu
conference: "Arxiv"
year: 2024
bibkey: lin2024constrained
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2409.13490'}
tags: ['Ethics and Bias', 'RAG', 'Prompting']
---
Theory-of-Mind (ToM) ability possessed by Large Language Models (LLMs) has
been shown to be limited. Most existing methods for improving ToM in LLMs adopt
zero-shot prompting, and they face challenges including poor performance in
complex ToM reasoning tasks and an inability to handle non-narrative contexts.
We propose a zero-shot prompting method named Constrained Chain-of-ToM (CCoToM)
that leverages domain knowledge and the causal relations between ToM dimensions
to address these limitations. Specifically, CCoToM guides LLMs to construct
explicit reasoning chains by first prompting LLMs to infer related ToM
dimensions (e.g., belief). Afterward, CCoToM prompts LLMs to infer the queried
ToM dimension based on the generated related ToM dimensions and corresponding
causal relations. Additionally, CCoToM adaptively imposes constraints on
prompts to introduce inductive biases and improve consistency between ToM
dimensions. Besides narratives, CCoToM can also handle non-narrative contexts
like conversations. Extensive experiments show that CCoToM consistently
outperforms previous state-of-the-art methods by large margins across all LLMs
and datasets used. We also conduct in-depth analyses to gain deeper insights
into CCoToM. We have made our code publicly available.
