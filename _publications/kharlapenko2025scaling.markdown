---
layout: publication
title: 'Scaling Sparse Feature Circuit Finding For In-context Learning'
authors: Dmitrii Kharlapenko, Stepan Shabalin, Fazl Barez, Arthur Conmy, Neel Nanda
conference: "Arxiv"
year: 2025
bibkey: kharlapenko2025scaling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.13756"}
tags: ['Interpretability and Explainability', 'Model Architecture', 'Reinforcement Learning', 'Attention Mechanism', 'Prompting', 'In-Context Learning']
---
Sparse autoencoders (SAEs) are a popular tool for interpreting large language
model activations, but their utility in addressing open questions in
interpretability remains unclear. In this work, we demonstrate their
effectiveness by using SAEs to deepen our understanding of the mechanism behind
in-context learning (ICL). We identify abstract SAE features that (i) encode
the model's knowledge of which task to execute and (ii) whose latent vectors
causally induce the task zero-shot. This aligns with prior work showing that
ICL is mediated by task vectors. We further demonstrate that these task vectors
are well approximated by a sparse sum of SAE latents, including these
task-execution features. To explore the ICL mechanism, we adapt the sparse
feature circuits methodology of Marks et al. (2024) to work for the much larger
Gemma-1 2B model, with 30 times as many parameters, and to the more complex
task of ICL. Through circuit finding, we discover task-detecting features with
corresponding SAE latents that activate earlier in the prompt, that detect when
tasks have been performed. They are causally linked with task-execution
features through the attention and MLP sublayers.
