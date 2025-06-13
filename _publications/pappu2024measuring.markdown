---
layout: publication
title: 'Measuring Memorization In RLHF For Code Completion'
authors: Aneesh Pappu, Billy Porter, Ilia Shumailov, Jamie Hayes
conference: "Arxiv"
year: 2024
bibkey: pappu2024measuring
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2406.11715'}
tags: ['Agentic', 'Efficiency and Optimization', 'Training Techniques', 'Fine-Tuning', 'Reinforcement Learning', 'Pretraining Methods']
---
Reinforcement learning with human feedback (RLHF) has become the dominant
method to align large models to user preferences. Unlike fine-tuning, for which
there are many studies regarding training data memorization, it is not clear
how memorization is affected by or introduced in the RLHF alignment process.
Understanding this relationship is important as real user data may be collected
and used to align large models; if user data is memorized during RLHF and later
regurgitated, this could raise privacy concerns. In addition to RLHF, other
methods such as Direct Preference Optimization (DPO) and \\(\Psi\\)PO have gained
popularity for learning directly from human preferences, removing the need for
optimizing intermediary reward models with reinforcement learning. In this
work, we analyze how training data memorization can surface and propagate
through each phase of RLHF and direct preference learning. We focus our study
on code completion models, as code completion is one of the most popular use
cases for large language models. We find that RLHF significantly decreases the
chance that data used for reward modeling and reinforcement learning is
memorized in comparison to directly fine-tuning on this data, but that examples
already memorized during the fine-tuning stage of RLHF, will, in the majority
of cases, remain memorized after RLHF. In contrast, we find that aligning by
learning directly from human preference data via a special case of \\(\Psi\\)PO,
Identity Preference Optimization (IPO), increases the likelihood that training
data is regurgitated compared to RLHF. Our work suggests that RLHF, as opposed
to direct preference learning, is a safer way to mitigate the risk of
regurgitating sensitive preference data when aligning large language models. We
find our conclusions are robust across multiple code completion datasets,
tasks, and model scales.
