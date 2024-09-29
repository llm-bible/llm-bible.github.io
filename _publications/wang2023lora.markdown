---
layout: publication
title: Lora Ensembles For Large Language Model Fine45;tuning
authors: Wang Xi, Aitchison Laurence, Rudolph Maja
conference: "Arxiv"
year: 2023
bibkey: wang2023lora
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.00035"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'Merging', 'Reinforcement Learning', 'Training Techniques']
---
Finetuned LLMs often exhibit poor uncertainty quantification manifesting as overconfidence poor calibration and unreliable prediction results on test data or out45;of45;distribution samples. One approach commonly used in vision for alleviating this issue is a deep ensemble which constructs an ensemble by training the same model multiple times using different random initializations. However there is a huge challenge to ensembling LLMs the most effective LLMs are very very large. Keeping a single LLM in memory is already challenging enough keeping an ensemble of e.g. 5 LLMs in memory is impossible in many settings. To address these issues we propose an ensemble approach using Low45;Rank Adapters (LoRA) a parameter45;efficient fine45;tuning technique. Critically these low45;rank adapters represent a very small number of parameters orders of magnitude less than the underlying pre45;trained model. Thus it is possible to construct large ensembles of LoRA adapters with almost the same computational overhead as using the original model. We find that LoRA ensembles applied on its own or on top of pre45;existing regularization techniques gives consistent improvements in predictive accuracy and uncertainty quantification.
