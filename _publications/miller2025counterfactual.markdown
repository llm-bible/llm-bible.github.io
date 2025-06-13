---
layout: publication
title: 'Counterfactual Reasoning: An Analysis Of In-context Emergence'
authors: Moritz Miller, Bernhard Schölkopf, Siyuan Guo
conference: "Arxiv"
year: 2025
bibkey: miller2025counterfactual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.05188"}
  - {name: "Code", url: "https://github.com/moXmiller/counterfactual-reasoning.git"}
tags: ['Transformer', 'Pre-Training', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Has Code', 'Pretraining Methods', 'Prompting', 'In-Context Learning']
---
Large-scale neural language models (LMs) exhibit remarkable performance in in-context learning: the ability to learn and reason the input context on the fly without parameter update. This work studies in-context counterfactual reasoning in language models, that is, to predict the consequences of changes under hypothetical scenarios. We focus on studying a well-defined synthetic setup: a linear regression task that requires noise abduction, where accurate prediction is based on inferring and copying the contextual noise from factual observations. We show that language models are capable of counterfactual reasoning in this controlled setup and provide insights that counterfactual reasoning for a broad class of functions can be reduced to a transformation on in-context observations; we find self-attention, model depth, and data diversity in pre-training drive performance in Transformers. More interestingly, our findings extend beyond regression tasks and show that Transformers can perform noise abduction on sequential data, providing preliminary evidence on the potential for counterfactual story generation. Our code is available under https://github.com/moXmiller/counterfactual-reasoning.git .
