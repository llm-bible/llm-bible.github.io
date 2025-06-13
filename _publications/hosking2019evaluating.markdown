---
layout: publication
title: 'Evaluating Rewards For Question Generation Models'
authors: Tom Hosking, Sebastian Riedel
conference: "Proceedings of the 2019 Conference of the North American Chapter of the Association for Computational Linguistics Human Language Technologies Volume 1 (Long and Short Papers)2278-2283"
year: 2019
bibkey: hosking2019evaluating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/1902.11049'}
tags: ['Agentic', 'Training Techniques', 'Applications', 'Model Architecture', 'Reinforcement Learning', 'Ethics and Bias']
---
Recent approaches to question generation have used modifications to a Seq2Seq
architecture inspired by advances in machine translation. Models are trained
using teacher forcing to optimise only the one-step-ahead prediction. However,
at test time, the model is asked to generate a whole sequence, causing errors
to propagate through the generation process (exposure bias). A number of
authors have proposed countering this bias by optimising for a reward that is
less tightly coupled to the training data, using reinforcement learning. We
optimise directly for quality metrics, including a novel approach using a
discriminator learned directly from the training data. We confirm that policy
gradient methods can be used to decouple training from the ground truth,
leading to increases in the metrics used as rewards. We perform a human
evaluation, and show that although these metrics have previously been assumed
to be good proxies for question quality, they are poorly aligned with human
judgement and the model simply learns to exploit the weaknesses of the reward
source.
