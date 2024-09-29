---
layout: publication
title: Large Language Models Can Implement Policy Iteration
authors: Brooks Ethan, Walls Logan, Lewis Richard L., Singh Satinder
conference: "Arxiv"
year: 2022
bibkey: brooks2022large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.03821"}
tags: ['Agentic', 'Attention Mechanism', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
This work presents In45;Context Policy Iteration an algorithm for performing Reinforcement Learning (RL) in45;context using foundation models. While the application of foundation models to RL has received considerable attention most approaches rely on either (1) the curation of expert demonstrations (either through manual design or task45;specific pretraining) or (2) adaptation to the task of interest using gradient methods (either fine45;tuning or training of adapter layers). Both of these techniques have drawbacks. Collecting demonstrations is labor45;intensive and algorithms that rely on them do not outperform the experts from which the demonstrations were derived. All gradient techniques are inherently slow sacrificing the few45;shot quality that made in45;context learning attractive to begin with. In this work we present an algorithm ICPI that learns to perform RL tasks without expert demonstrations or gradients. Instead we present a policy45;iteration method in which the prompt content is the entire locus of learning. ICPI iteratively updates the contents of the prompt from which it derives its policy through trial45;and45;error interaction with an RL environment. In order to eliminate the role of in45;weights learning (on which approaches like Decision Transformer rely heavily) we demonstrate our algorithm using Codex a language model with no prior knowledge of the domains on which we evaluate it.
