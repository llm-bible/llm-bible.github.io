---
layout: publication
title: Learning To Diversify For Product Question Generation
authors: Roitman Haggai, Singer Uriel, Eshel Yotam, Nus Alexander, Kiperwasser Eliyahu
conference: "Arxiv"
year: 2022
bibkey: roitman2022learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2207.02534"}
tags: ['Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Transformer']
---
We address the product question generation task. For a given product description our goal is to generate questions that reflect potential user information needs that are either missing or not well covered in the description. Moreover we wish to cover diverse user information needs that may span a multitude of product types. To this end we first show how the T5 pre45;trained Transformer encoder45;decoder model can be fine45;tuned for the task. Yet while the T5 generated questions have a reasonable quality compared to the state45;of45;the45;art method for the task (KPCNet) many of such questions are still too general resulting in a sub45;optimal global question diversity. As an alternative we propose a novel learning45;to45;diversify (LTD) fine45;tuning approach that allows to enrich the language learned by the underlying Transformer model. Our empirical evaluation shows that using our approach significantly improves the global diversity of the underlying Transformer model while preserves as much as possible its generation relevance.
