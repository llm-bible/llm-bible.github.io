---
layout: publication
title: 'Supervising The Transfer Of Reasoning Patterns In VQA'
authors: Corentin Kervadec, Christian Wolf, Grigory Antipov, Moez Baccouche, Madiha Nadri
conference: "Arxiv"
year: 2021
bibkey: kervadec2021supervising
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2106.05597'}
tags: ['Attention Mechanism', 'ACL', 'RAG', 'Pre-Training', 'Model Architecture', 'Training Techniques', 'BERT', 'Ethics and Bias']
---
Methods for Visual Question Anwering (VQA) are notorious for leveraging
dataset biases rather than performing reasoning, hindering generalization. It
has been recently shown that better reasoning patterns emerge in attention
layers of a state-of-the-art VQA model when they are trained on perfect
(oracle) visual inputs. This provides evidence that deep neural networks can
learn to reason when training conditions are favorable enough. However,
transferring this learned knowledge to deployable models is a challenge, as
much of it is lost during the transfer. We propose a method for knowledge
transfer based on a regularization term in our loss function, supervising the
sequence of required reasoning operations. We provide a theoretical analysis
based on PAC-learning, showing that such program prediction can lead to
decreased sample complexity under mild hypotheses. We also demonstrate the
effectiveness of this approach experimentally on the GQA dataset and show its
complementarity to BERT-like self-supervised pre-training.
