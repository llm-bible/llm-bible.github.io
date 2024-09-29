---
layout: publication
title: Reasoning In Transformers -- Mitigating Spurious Correlations And Reasoning Shortcuts
authors: Enström Daniel, Kjellberg Viktor, Johansson Moa
conference: "Arxiv"
year: 2024
bibkey: enström2024reasoning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.11314"}
tags: ['Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Transformer language models are neural networks used for a wide variety of tasks concerning natural language including some that also require logical reasoning. However a transformer model may easily learn spurious patterns in the data short-circuiting actual reasoning. In this paper we investigate to what extent transformers can be trained to a) approximate reasoning in propositional logic while b) avoiding known reasoning shortcuts via spurious correlations in the training data. To do so we use a dataset with known spurious correlation between truth and e.g. the number of rules in the problem. We augment the data with proofs and train two models a generative transformer WP-BART trained on problems and their whole proofs and a neuro-symbolic model SIP-BART trained on individual proof steps and combining the generative transformer model BART with a symbolic proof checker. We find that SIP-BART succeeds in avoiding reasoning shortcuts while WP-BART does not. For SIP-BART we then identify a few remaining reasoning errors not previously described in the literature arising from using a pre-trained language model. These are qualitatively analysed to create a taxonomy of four different types of additional pitfalls.
