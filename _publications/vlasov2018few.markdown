---
layout: publication
title: 'Few-shot Generalization Across Dialogue Tasks'
authors: Vladimir Vlasov, Akela Drissner-schmid, Alan Nichol
conference: "Arxiv"
year: 2018
bibkey: vlasov2018few
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1811.11707"}
tags: ['Few-Shot', 'Attention Mechanism', 'Transformer', 'Model Architecture']
---
Machine-learning based dialogue managers are able to learn complex behaviors
in order to complete a task, but it is not straightforward to extend their
capabilities to new domains. We investigate different policies' ability to
handle uncooperative user behavior, and how well expertise in completing one
task (such as restaurant reservations) can be reapplied when learning a new one
(e.g. booking a hotel). We introduce the Recurrent Embedding Dialogue Policy
(REDP), which embeds system actions and dialogue states in the same vector
space. REDP contains a memory component and attention mechanism based on a
modified Neural Turing Machine, and significantly outperforms a baseline LSTM
classifier on this task. We also show that both our architecture and baseline
solve the bAbI dialogue task, achieving 100% test accuracy.
