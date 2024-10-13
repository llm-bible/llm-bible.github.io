---
layout: publication
title: 'Examining Llms'' Uncertainty Expression Towards Questions Outside Parametric Knowledge'
authors: Liu Genglin, Wang Xingyao, Yuan Lifan, Chen Yangyi, Peng Hao
conference: "Arxiv"
year: 2023
bibkey: liu2023examining
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.09731"}
tags: ['Fine Tuning', 'Pretraining Methods', 'Training Techniques']
---
Can large language models (LLMs) express their uncertainty in situations
where they lack sufficient parametric knowledge to generate reasonable
responses? This work aims to systematically investigate LLMs' behaviors in such
situations, emphasizing the trade-off between honesty and helpfulness. To
tackle the challenge of precisely determining LLMs' knowledge gaps, we
diagnostically create unanswerable questions containing non-existent concepts
or false premises, ensuring that they are outside the LLMs' vast training data.
By compiling a benchmark, UnknownBench, which consists of both unanswerable and
answerable questions, we quantitatively evaluate the LLMs' performance in
maintaining honesty while being helpful. Using a model-agnostic unified
confidence elicitation approach, we observe that most LLMs fail to consistently
refuse or express uncertainty towards questions outside their parametric
knowledge, although instruction fine-tuning and alignment techniques can
provide marginal enhancements. Moreover, LLMs' uncertainty expression does not
always stay consistent with the perceived confidence of their textual outputs.
