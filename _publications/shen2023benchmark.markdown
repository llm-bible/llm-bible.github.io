---
layout: publication
title: 'Graphextqa: A Benchmark For Evaluating Graph-enhanced Large Language Models'
authors: Shen Yuanchun, Liao Ruotong, Han Zhen, Ma Yunpu, Tresp Volker
conference: "Arxiv"
year: 2023
bibkey: shen2023benchmark
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.08487"}
tags: ['Applications', 'Language Modeling', 'Multimodal Models']
---
While multi-modal models have successfully integrated information from image,
video, and audio modalities, integrating graph modality into large language
models (LLMs) remains unexplored. This discrepancy largely stems from the
inherent divergence between structured graph data and unstructured text data.
Incorporating graph knowledge provides a reliable source of information,
enabling potential solutions to address issues in text generation, e.g.,
hallucination, and lack of domain knowledge. To evaluate the integration of
graph knowledge into language models, a dedicated dataset is needed. However,
there is currently no benchmark dataset specifically designed for multimodal
graph-language models. To address this gap, we propose GraphextQA, a question
answering dataset with paired subgraphs, retrieved from Wikidata, to facilitate
the evaluation and future development of graph-language models. Additionally,
we introduce a baseline model called CrossGNN, which conditions answer
generation on the paired graphs by cross-attending question-aware graph
features at decoding. The proposed dataset is designed to evaluate
graph-language models' ability to understand graphs and make use of it for
answer generation. We perform experiments with language-only models and the
proposed graph-language model to validate the usefulness of the paired graphs
and to demonstrate the difficulty of the task.
