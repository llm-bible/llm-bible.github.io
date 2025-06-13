---
layout: publication
title: 'Modifying Memories In Transformer Models'
authors: Chen Zhu, Ankit Singh Rawat, Manzil Zaheer, Srinadh Bhojanapalli, Daliang Li, Felix Yu, Sanjiv Kumar
conference: "Arxiv"
year: 2020
bibkey: zhu2020modifying
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2012.00363'}
tags: ['Transformer', 'Training Techniques', 'Model Architecture', 'Fine-Tuning', 'Ethics and Bias', 'Pretraining Methods']
---
Large Transformer models have achieved impressive performance in many natural
language tasks. In particular, Transformer based language models have been
shown to have great capabilities in encoding factual knowledge in their vast
amount of parameters. While the tasks of improving the memorization and
generalization of Transformers have been widely studied, it is not well known
how to make transformers forget specific old facts and memorize new ones. In
this paper, we propose a new task of *explicitly modifying specific
factual knowledge in Transformer models while ensuring the model performance
does not degrade on the unmodified facts*. This task is useful in many
scenarios, such as updating stale knowledge, protecting privacy, and
eliminating unintended biases stored in the models. We benchmarked several
approaches that provide natural baseline performances on this task. This leads
to the discovery of key components of a Transformer model that are especially
effective for knowledge modifications. The work also provides insights into the
role that different training phases (such as pretraining and fine-tuning) play
towards memorization and knowledge modification.
