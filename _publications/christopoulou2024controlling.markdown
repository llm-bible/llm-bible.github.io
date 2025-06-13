---
layout: publication
title: 'Sparsepo: Controlling Preference Alignment Of Llms Via Sparse Token Masks'
authors: Fenia Christopoulou, Ronald Cardenas, Gerasimos Lampouras, Haitham Bou-ammar, Jun Wang
conference: "Arxiv"
year: 2024
bibkey: christopoulou2024controlling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.05102"}
tags: ['Training Techniques', 'Efficiency and Optimization', 'Applications', 'Reinforcement Learning']
---
Preference Optimization (PO) has proven an effective step for aligning
language models to human-desired behaviors. Current variants, following the
offline Direct Preference Optimization objective, have focused on a strict
setting where all tokens are contributing signals of KL divergence and rewards
to the loss function. However, human preference is not affected by each word in
a sequence equally but is often dependent on specific words or phrases, e.g.
existence of toxic terms leads to non-preferred responses. Based on this
observation, we argue that not all tokens should be weighted equally during PO
and propose a flexible objective termed SparsePO, that aims to automatically
learn to weight the KL divergence and reward corresponding to each token during
PO training. We propose two different variants of weight-masks that can either
be derived from the reference model itself or learned on the fly. Notably, our
method induces sparsity in the learned masks, allowing the model to learn how
to best weight reward and KL divergence contributions at the token level,
learning an optimal level of mask sparsity. Extensive experiments on multiple
domains, including sentiment control, dialogue, text summarization and
text-to-code generation, illustrate that our approach assigns meaningful
weights to tokens according to the target task, generates more responses with
the desired preference and improves reasoning tasks by up to 2 percentage
points compared to other token- and response-level PO methods.
