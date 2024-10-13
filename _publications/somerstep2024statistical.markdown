---
layout: publication
title: 'A Statistical Framework For Weak-to-strong Generalization'
authors: Somerstep Seamus, Polo Felipe Maia, Banerjee Moulinath, Ritov Ya'acov, Yurochkin Mikhail, Sun Yuekai
conference: "Arxiv"
year: 2024
bibkey: somerstep2024statistical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.16236"}
tags: ['Fine Tuning', 'Pretraining Methods', 'Tools', 'Training Techniques']
---
Modern large language model (LLM) alignment techniques rely on human
feedback, but it is unclear whether the techniques fundamentally limit the
capabilities of aligned LLMs. In particular, it is unclear whether it is
possible to align (stronger) LLMs with superhuman capabilities with (weaker)
human feedback without degrading their capabilities. This is an instance of the
weak-to-strong generalization problem: using weaker (less capable) feedback to
train a stronger (more capable) model. We prove that weak-to-strong
generalization is possible by eliciting latent knowledge from pre-trained LLMs.
In particular, we cast the weak-to-strong generalization problem as a transfer
learning problem in which we wish to transfer a latent concept from a weak
model to a strong pre-trained model. We prove that a naive fine-tuning approach
suffers from fundamental limitations, but an alternative refinement-based
approach suggested by the problem structure provably overcomes the limitations
of fine-tuning. Finally, we demonstrate the practical applicability of the
refinement approach with three LLM alignment tasks.
