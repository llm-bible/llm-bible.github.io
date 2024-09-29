---
layout: publication
title: Learning to Decode Collaboratively with Multiple Language Models
authors: Shen Shannon Zejiang, Lang Hunter, Wang Bailin, Kim Yoon, Sontag David
conference: "Arxiv"
year: 2024
bibkey: shen2024learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.03870"}
  - {name: "Code", url: "https://github.com/clinicalml/co-llm"}
tags: ['Has Code', 'Merging', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
We propose a method to teach multiple large language models (LLM) to collaborate by interleaving their generations at the token level. We model the decision of which LLM generates the next token as a latent variable. By optimizing the marginal likelihood of a training set under our latent variable model the base LLM automatically learns when to generate itself and when to call on one of the assistant language models to generate all without direct supervision. Token-level collaboration during decoding allows for a fusion of each models expertise in a manner tailored to the specific task at hand. Our collaborative decoding is especially useful in cross-domain settings where a generalist base LLM learns to invoke domain expert models. On instruction-following domain-specific QA and reasoning tasks we show that the performance of the joint system exceeds that of the individual models. Through qualitative analysis of the learned latent decisions we show models trained with our method exhibit several interesting collaboration patterns e.g. template-filling. Our code is available at https://github.com/clinicalml/co-llm.
