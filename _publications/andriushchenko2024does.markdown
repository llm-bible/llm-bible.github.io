---
layout: publication
title: "Does Refusal Training In Llms Generalize To The Past Tense?"
authors: Andriushchenko Maksym, Flammarion Nicolas
conference: "Arxiv"
year: 2024
bibkey: andriushchenko2024does
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.11969"}
  - {name: "Code", url: "https://github.com/tml-epfl/llm-past-tense"}
tags: ['Fine Tuning', 'GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Security', 'Training Techniques']
---
Refusal training is widely used to prevent LLMs from generating harmful undesirable or illegal outputs. We reveal a curious generalization gap in the current refusal training approaches simply reformulating a harmful request in the past tense (e.g. How to make a Molotov cocktail to How did people make a Molotov cocktail) is often sufficient to jailbreak many state-of-the-art LLMs. We systematically evaluate this method on Llama-3 8B Claude-3.5 Sonnet GPT-3.5 Turbo Gemma-2 9B Phi-3-Mini GPT-4o mini GPT-4o and R2D2 models using GPT-3.5 Turbo as a reformulation model. For example the success rate of this simple attack on GPT-4o increases from 137; using direct requests to 8837; using 20 past tense reformulation attempts on harmful requests from JailbreakBench with GPT-4 as a jailbreak judge. Interestingly we also find that reformulations in the future tense are less effective suggesting that refusal guardrails tend to consider past historical questions more benign than hypothetical future questions. Moreover our experiments on fine-tuning GPT-3.5 Turbo show that defending against past reformulations is feasible when past tense examples are explicitly included in the fine-tuning data. Overall our findings highlight that the widely used alignment techniques -- such as SFT RLHF and adversarial training -- employed to align the studied models can be brittle and do not always generalize as intended. We provide code and jailbreak artifacts at https://github.com/tml-epfl/llm-past-tense."
