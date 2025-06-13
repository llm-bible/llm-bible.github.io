---
layout: publication
title: 'An Extensive Evaluation Of Factual Consistency In Large Language Models For Data-to-text Generation'
authors: Joy Mahapatra, Utpal Garain
conference: "Arxiv"
year: 2024
bibkey: mahapatra2024extensive
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.19203'}
tags: ['RAG', 'Language Modeling', 'Applications']
---
Large Language Models (LLMs) have shown exceptional performance across
various Data-to-Text Generation (DTG) tasks. However, generating factually
consistent text in DTG remains challenging for LLMs. Despite this, in-depth
evaluations of LLM factual consistency for DTG remain missing in the current
literature. This paper addresses this gap by providing an extensive evaluation
of factual consistency in LLMs for DTG. Our evaluation covers five widely used
DTG datasets (E2E, ViGGo, WikiTableText, DART, and WebNLG) and five prominent
LLM families (T5, BART, OPT, BLOOM, and Llama 2). To ensure a thorough
evaluation of factual consistency, we use four state-of-the-art automatic
metrics and include essential human assessments. Our extensive evaluations
reveals three key findings regarding factual consistency in LLMs for DTG.
First, Llama 2 often excels in generating factually consistent text, although
smaller models like T5 and BART can achieve strong factual consistency on
larger, lexically less-diverse datasets. Second, the average rate of change
(AROC) indicates that increasing model size (number of model trainable
parameters) generally enhances factual consistency of LLMs in DTG. Third, we
observe that source-reference divergence (i.e., when the reference text
diverges semantically from the source) typically reduces the factual
consistency of LLMs in DTG.
