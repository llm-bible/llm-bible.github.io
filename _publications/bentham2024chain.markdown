---
layout: publication
title: Chain45;of45;thought Unfaithfulness As Disguised Accuracy
authors: Bentham Oliver, Stringham Nathan, Marasović Ana
conference: "Arxiv"
year: 2024
bibkey: bentham2024chain
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.14897"}
tags: ['Ethics And Bias']
---
Understanding the extent to which Chain45;of45;Thought (CoT) generations align with a large language models (LLM) internal computations is critical for deciding whether to trust an LLMs output. As a proxy for CoT faithfulness Lanham et al. (2023) propose a metric that measures a models dependence on its CoT for producing an answer. Within a single family of proprietary models they find that LLMs exhibit a scaling45;then45;inverse45;scaling relationship between model size and their measure of faithfulness and that a 13 billion parameter model exhibits increased faithfulness compared to models ranging from 810 million to 175 billion parameters in size. We evaluate whether these results generalize as a property of all LLMs. We replicate the experimental setup in their section focused on scaling experiments with three different families of models and under specific conditions successfully reproduce the scaling trends for CoT faithfulness they report. However after normalizing the metric to account for a models bias toward certain answer choices unfaithfulness drops significantly for smaller less45;capable models. This normalized faithfulness metric is also strongly correlated (R^2=0.74) with accuracy raising doubts about its validity for evaluating faithfulness.
