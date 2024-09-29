---
layout: publication
title: "Removing RLHF Protections In GPT-4 Via Fine-tuning"
authors: Zhan Qiusi, Fang Richard, Bindu Rohan, Gupta Akul, Hashimoto Tatsunori, Kang Daniel
conference: "Arxiv"
year: 2023
bibkey: zhan2023removing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.05553"}
tags: ['Agentic', 'Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Security', 'Training Techniques']
---
As large language models (LLMs) have increased in their capabilities so does their potential for dual use. To reduce harmful outputs produces and vendors of LLMs have used reinforcement learning with human feedback (RLHF). In tandem LLM vendors have been increasingly enabling fine-tuning of their most powerful models. However concurrent work has shown that fine-tuning can remove RLHF protections. We may expect that the most powerful models currently available (GPT-4) are less susceptible to fine-tuning attacks. In this work we show the contrary fine-tuning allows attackers to remove RLHF protections with as few as 340 examples and a 9537; success rate. These training examples can be automatically generated with weaker models. We further show that removing RLHF protections does not decrease usefulness on non-censored outputs providing evidence that our fine-tuning strategy does not decrease usefulness despite using weaker models to generate training data. Our results show the need for further research on protections on LLMs.
