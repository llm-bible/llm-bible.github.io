---
layout: publication
title: An Explanation Of In45;context Learning As Implicit Bayesian Inference
authors: Xie Sang Michael, Raghunathan Aditi, Liang Percy, Ma Tengyu
conference: "Arxiv"
year: 2021
bibkey: xie2021explanation
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2111.02080"}
tags: ['GPT', 'Interpretability And Explainability', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Scaling Laws', 'Training Techniques', 'Transformer']
---
Large language models (LMs) such as GPT45;3 have the surprising ability to do in45;context learning where the model learns to do a downstream task simply by conditioning on a prompt consisting of input45;output examples. The LM learns from these examples without being explicitly pretrained to learn. Thus it is unclear what enables in45;context learning. In this paper we study how in45;context learning can emerge when pretraining documents have long45;range coherence. Here the LM must infer a latent document45;level concept to generate coherent next tokens during pretraining. At test time in45;context learning occurs when the LM also infers a shared latent concept between examples in a prompt. We prove when this occurs despite a distribution mismatch between prompts and pretraining data in a setting where the pretraining distribution is a mixture of HMMs. In contrast to messy large45;scale datasets used to train LMs capable of in45;context learning we generate a small45;scale synthetic dataset (GINC) where Transformers and LSTMs both exhibit in45;context learning. Beyond the theory experiments on GINC exhibit large45;scale real45;world phenomena including improved in45;context performance with model scaling (despite the same pretraining loss) sensitivity to example order and instances where zero45;shot is better than few45;shot in45;context learning.
