---
layout: publication
title: 'Linguistic Calibration Of Long-form Generations'
authors: Band Neil, Li Xuechen, Ma Tengyu, Hashimoto Tatsunori
conference: "Arxiv"
year: 2024
bibkey: band2024linguistic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.00474"}
tags: ['Agentic', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Language models (LMs) may lead their users to make suboptimal downstream
decisions when they confidently hallucinate. This issue can be mitigated by
having the LM verbally convey the probability that its claims are correct, but
existing models cannot produce long-form text with calibrated confidence
statements. Through the lens of decision-making, we define linguistic
calibration for long-form generations: an LM is linguistically calibrated if
its generations enable its users to make calibrated probabilistic predictions.
This definition enables a training framework where a supervised finetuning step
bootstraps an LM to emit long-form generations with confidence statements such
as "I estimate a 30% chance of..." or "I am certain that...", followed by a
reinforcement learning step which rewards generations that enable a user to
provide calibrated answers to related questions. We linguistically calibrate
Llama 2 7B and find in automated and human evaluations of long-form generations
that it is significantly more calibrated than strong finetuned factuality
baselines with comparable accuracy. These findings generalize under significant
domain shifts to scientific and biomedical questions and to an entirely
held-out person biography generation task. Our results demonstrate that
long-form generations may be calibrated end-to-end by constructing an objective
in the space of the predictions that users make in downstream decision-making.
