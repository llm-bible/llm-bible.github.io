---
layout: publication
title: 'Test-time Training Provably Improves Transformers As In-context Learners'
authors: Halil Alperen Gozeten, M. Emrullah Ildiz, Xuechen Zhang, Mahdi Soltanolkotabi, Marco Mondelli, Samet Oymak
conference: "Arxiv"
year: 2025
bibkey: gozeten2025test
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.11842"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Language Modeling', 'Pretraining Methods', 'Transformer', 'Prompting', 'In-Context Learning']
---
Test-time training (TTT) methods explicitly update the weights of a model to
adapt to the specific test instance, and they have found success in a variety
of settings, including most recently language modeling and reasoning. To
demystify this success, we investigate a gradient-based TTT algorithm for
in-context learning, where we train a transformer model on the in-context
demonstrations provided in the test prompt. Specifically, we provide a
comprehensive theoretical characterization of linear transformers when the
update rule is a single gradient step. Our theory (i) delineates the role of
alignment between pretraining distribution and target task, (ii) demystifies
how TTT can alleviate distribution shift, and (iii) quantifies the sample
complexity of TTT including how it can significantly reduce the eventual sample
size required for in-context learning. As our empirical contribution, we study
the benefits of TTT for TabPFN, a tabular foundation model. In line with our
theory, we demonstrate that TTT significantly reduces the required sample size
for tabular classification (3 to 5 times fewer) unlocking substantial inference
efficiency with a negligible training cost.
