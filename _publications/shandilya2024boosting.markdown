---
layout: publication
title: 'Boosting The Capabilities Of Compact Models In Low-data Contexts With Large Language Models And Retrieval-augmented Generation'
authors: Bhargav Shandilya, Alexis Palmer
conference: "Arxiv"
year: 2024
bibkey: shandilya2024boosting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.00387"}
tags: ['Tools', 'Efficiency and Optimization', 'Ethics and Bias', 'Interpretability and Explainability', 'RAG', 'Language Modeling', 'Reinforcement Learning']
---
The data and compute requirements of current language modeling technology
pose challenges for the processing and analysis of low-resource languages.
Declarative linguistic knowledge has the potential to partially bridge this
data scarcity gap by providing models with useful inductive bias in the form of
language-specific rules. In this paper, we propose a retrieval augmented
generation (RAG) framework backed by a large language model (LLM) to correct
the output of a smaller model for the linguistic task of morphological
glossing. We leverage linguistic information to make up for the lack of data
and trainable parameters, while allowing for inputs from written descriptive
grammars interpreted and distilled through an LLM.
  The results demonstrate that significant leaps in performance and efficiency
are possible with the right combination of: a) linguistic inputs in the form of
grammars, b) the interpretive power of LLMs, and c) the trainability of smaller
token classification networks. We show that a compact, RAG-supported model is
highly effective in data-scarce settings, achieving a new state-of-the-art for
this task and our target languages. Our work also offers documentary linguists
a more reliable and more usable tool for morphological glossing by providing
well-reasoned explanations and confidence scores for each output.
