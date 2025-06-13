---
layout: publication
title: 'Graph-dpep: Decomposed Plug And Ensemble Play For Few-shot Document Relation Extraction With Graph-of-thoughts Reasoning'
authors: Tao Zhang, Ning Yan, Masood Mortazavi, Hoang H. Nguyen, Zhongfen Deng, Philip S. Yu
conference: "Arxiv"
year: 2024
bibkey: zhang2024graph
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.02864"}
tags: ['Few-Shot', 'Tools', 'Reinforcement Learning', 'Language Modeling', 'RAG', 'Interpretability and Explainability', 'Prompting', 'Applications']
---
Large language models (LLMs) pre-trained on massive corpora have demonstrated
impressive few-shot learning capability on many NLP tasks. Recasting an NLP
task into a text-to-text generation task is a common practice so that
generative LLMs can be prompted to resolve it. However, performing
document-level relation extraction (DocRE) tasks with generative LLM models is
still challenging due to the structured output format of DocRE, which
complicates the conversion to plain text. Limited information available in
few-shot samples and prompt instructions induce further difficulties and
challenges in relation extraction for mentioned entities in a document. In this
paper, we represent the structured output as a graph-style triplet rather than
natural language expressions and leverage generative LLMs for the DocRE task.
Our approach, the Graph-DPEP framework is grounded in the reasoning behind
triplet explanation thoughts presented in natural language. In this framework,
we first introduce a ``decomposed-plug" method for performing the generation
from LLMs over prompts with type-space decomposition to alleviate the burden of
distinguishing all relation types. Second, we employ a verifier for calibrating
the generation and identifying overlooked query entity pairs. Third, we develop
"ensemble-play", reapplying generation on the entire type list by leveraging
the reasoning thoughts embedded in a sub-graph associated with the missing
query pair to address the missingness issue. Through extensive comparisons with
existing prompt techniques and alternative Language Models (LLMs), our
framework demonstrates superior performance on publicly available benchmarks in
experiments.
