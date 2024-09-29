---
layout: publication
title: "Pii-compass: Guiding LLM Training Data Extraction Prompts Towards The Target PII Via Grounding"
authors: Nakka Krishna Kanth, Frikha Ahmed, Mendes Ricardo, Jiang Xue, Zhou Xuebing
conference: "Arxiv"
year: 2024
bibkey: nakka2024pii
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.02943"}
tags: ['Ethics And Bias', 'Prompting', 'Training Techniques']
---
The latest and most impactful advances in large models stem from their increased size. Unfortunately this translates into an improved memorization capacity raising data privacy concerns. Specifically it has been shown that models can output personal identifiable information (PII) contained in their training data. However reported PIII extraction performance varies widely and there is no consensus on the optimal methodology to evaluate this risk resulting in underestimating realistic adversaries. In this work we empirically demonstrate that it is possible to improve the extractability of PII by over ten-fold by grounding the prefix of the manually constructed extraction prompt with in-domain data. Our approach PII-Compass achieves phone number extraction rates of 0.9237; 3.937; and 6.8637; with 1 128 and 2308 queries respectively i.e. the phone number of 1 person in 15 is extractable.
