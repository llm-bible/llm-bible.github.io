---
layout: publication
title: Does Refusal Training In Llms Generalize To The Past Tense
authors: Andriushchenko Maksym, Flammarion Nicolas
conference: "Arxiv"
year: 2024
bibkey: andriushchenko2024does
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.11969"}
  - {name: "Code", url: "https://github.com/tml&#45;epfl/llm&#45;past&#45;tense"}
tags: ['Ethics And Bias', 'Fine Tuning', 'GPT', 'Has Code', 'Model Architecture', 'Reinforcement Learning', 'Security', 'Training Techniques']
---
Refusal training is widely used to prevent LLMs from generating harmful undesirable or illegal outputs. We reveal a curious generalization gap in the current refusal training approaches simply reformulating a harmful request in the past tense (e.g. How to make a Molotov cocktail to How did people make a Molotov cocktail) is often sufficient to jailbreak many state45;of45;the45;art LLMs. We systematically evaluate this method on Llama45;3 8B Claude45;3.5 Sonnet GPT45;3.5 Turbo Gemma45;2 9B Phi45;345;Mini GPT45;4o mini GPT45;4o and R2D2 models using GPT45;3.5 Turbo as a reformulation model. For example the success rate of this simple attack on GPT45;4o increases from 137; using direct requests to 8837; using 20 past tense reformulation attempts on harmful requests from JailbreakBench with GPT45;4 as a jailbreak judge. Interestingly we also find that reformulations in the future tense are less effective suggesting that refusal guardrails tend to consider past historical questions more benign than hypothetical future questions. Moreover our experiments on fine45;tuning GPT45;3.5 Turbo show that defending against past reformulations is feasible when past tense examples are explicitly included in the fine45;tuning data. Overall our findings highlight that the widely used alignment techniques 45;45; such as SFT RLHF and adversarial training 45;45; employed to align the studied models can be brittle and do not always generalize as intended. We provide code and jailbreak artifacts at https://github.com/tml&#45;epfl/llm&#45;past&#45;tense.
