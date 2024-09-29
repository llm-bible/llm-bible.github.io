---
layout: publication
title: Does Fine45;tuning Llms On New Knowledge Encourage Hallucinations
authors: Gekhman Zorik, Yona Gal, Aharoni Roee, Eyal Matan, Feder Amir, Reichart Roi, Herzig Jonathan
conference: "Arxiv"
year: 2024
bibkey: gekhman2024does
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.05904"}
tags: ['Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
When large language models are aligned via supervised fine45;tuning they may encounter new factual information that was not acquired through pre45;training. It is often conjectured that this can teach the model the behavior of hallucinating factually incorrect responses as the model is trained to generate facts that are not grounded in its pre45;existing knowledge. In this work we study the impact of such exposure to new knowledge on the capability of the fine45;tuned model to utilize its pre45;existing knowledge. To this end we design a controlled setup focused on closed45;book QA where we vary the proportion of the fine45;tuning examples that introduce new knowledge. We demonstrate that large language models struggle to acquire new factual knowledge through fine45;tuning as fine45;tuning examples that introduce new knowledge are learned significantly slower than those consistent with the models knowledge. However we also find that as the examples with new knowledge are eventually learned they linearly increase the models tendency to hallucinate. Taken together our results highlight the risk in introducing new factual knowledge through fine45;tuning and support the view that large language models mostly acquire factual knowledge through pre45;training whereas fine45;tuning teaches them to use it more efficiently.
