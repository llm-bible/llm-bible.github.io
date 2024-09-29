---
layout: publication
title: ExaRanker Explanation-Augmented Neural Ranker
authors: Ferraretto Fernando, Laitz Thiago, Lotufo Roberto, Nogueira Rodrigo
conference: "Arxiv"
year: 2023
bibkey: ferraretto2023exaranker
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2301.10521"}
tags: ['GPT', 'Interpretability And Explainability', 'Model Architecture', 'Pretraining Methods']
---
Recent work has shown that inducing a large language model (LLM) to generate explanations prior to outputting an answer is an effective strategy to improve performance on a wide range of reasoning tasks. In this work we show that neural rankers also benefit from explanations. We use LLMs such as GPT-3.5 to augment retrieval datasets with explanations and train a sequence-to-sequence ranking model to output a relevance label and an explanation for a given query-document pair. Our model dubbed ExaRanker finetuned on a few thousand examples with synthetic explanations performs on par with models finetuned on 3x more examples without explanations. Furthermore the ExaRanker model incurs no additional computational cost during ranking and allows explanations to be requested on demand.
