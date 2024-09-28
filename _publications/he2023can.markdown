---
layout: publication
title: Can ChatGPT Detect Intent Evaluating Large Language Models for Spoken Language Understanding
authors: He Mutian, Garner Philip N.
conference: "Arxiv"
year: 2023
bibkey: he2023can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.13512"}
tags: ['Supervised', 'Applications', 'Arxiv']
---
Recently large pretrained language models have demonstrated strong language understanding capabilities. This is particularly reflected in their zero-shot and in-context learning abilities on downstream tasks through prompting. To assess their impact on spoken language understanding (SLU) we evaluate several such models like ChatGPT and OPT of different sizes on multiple benchmarks. We verify the emergent ability unique to the largest models as they can reach intent classification accuracy close to that of supervised models with zero or few shots on various languages given oracle transcripts. By contrast the results for smaller models fitting a single GPU fall far behind. We note that the error cases often arise from the annotation scheme of the dataset; responses from ChatGPT are still reasonable. We show however that the model is worse at slot filling and its performance is sensitive to ASR errors suggesting serious challenges for the application of those textual models on SLU.
