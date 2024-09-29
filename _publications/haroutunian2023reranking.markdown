---
layout: publication
title: "Reranking For Natural Language Generation From Logical Forms: A Study Based On Large Language Models"
authors: Haroutunian Levon, Li Zhuang, Galescu Lucian, Cohen Philip, Tumuluri Raj, Haffari Gholamreza
conference: "Arxiv"
year: 2023
bibkey: haroutunian2023reranking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.12294"}
tags: ['Ethics And Bias', 'Prompting', 'Training Techniques']
---
Large language models (LLMs) have demonstrated impressive capabilities in natural language generation. However their output quality can be inconsistent posing challenges for generating natural language from logical forms (LFs). This task requires the generated outputs to embody the exact semantics of LFs without missing any LF semantics or creating any hallucinations. In this work we tackle this issue by proposing a novel generate-and-rerank approach. Our approach involves initially generating a set of candidate outputs by prompting an LLM and subsequently reranking them using a task-specific reranker model. In addition we curate a manually collected dataset to evaluate the alignment between different ranking metrics and human judgements. The chosen ranking metrics are utilized to enhance the training and evaluation of the reranker model. By conducting extensive experiments on three diverse datasets we demonstrate that the candidates selected by our reranker outperform those selected by baseline methods in terms of semantic consistency and fluency as measured by three comprehensive metrics. Our findings provide strong evidence for the effectiveness of our approach in improving the quality of generated outputs.
