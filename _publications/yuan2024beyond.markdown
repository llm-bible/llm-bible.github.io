---
layout: publication
title: 'Beyond Under-alignment: Atomic Preference Enhanced Factuality Tuning For Large Language Models'
authors: Yuan Hongbang, Chen Yubo, Cao Pengfei, Jin Zhuoran, Liu Kang, Zhao Jun
conference: "Arxiv"
year: 2024
bibkey: yuan2024beyond
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.12416"}
tags: ['RAG', 'Tools']
---
Large language models (LLMs) have achieved remarkable success but still tend
to generate factually erroneous responses, a phenomenon known as hallucination.
A recent trend is to use preference learning to fine-tune models to align with
factuality. However, existing work primarily evaluates fine-tuned models on
in-domain (ID) datasets and the factuality on out-of-domain (OOD) datasets
remains underexplored. In this paper, we conduct a comprehensive evaluation of
the factuality of different models tuned by various preference learning
algorithms and demonstrate that their performance on OOD datasets either
increases minimally or decreases. Subsequently, we reveal that the main cause
of model's failure to uphold factuality under a distribution shift is
\textbf\{under-alignment\}, rather than \textbf\{over-alignment\}, by analyzing the
token distribution shift of the models before and after tuning. Finally, we
propose \textbf\{APEFT\} (\textbf\{A\}tomic \textbf\{P\}reference \textbf\{E\}nhanced
\textbf\{F\}actuality \textbf\{T\}uning), a framework that enhances model's
awareness of factuality at the granularity of individual facts. Extensive
experiments demonstrate that APEFT improves model performance by an average of
\\(\boldsymbol\{3.45%\}\\) on both ID and OOD datasets, which is highly effective.
