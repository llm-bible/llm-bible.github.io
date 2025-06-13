---
layout: publication
title: 'A Little Help Goes A Long Way: Efficient LLM Training By Leveraging Small Lms'
authors: Ankit Singh Rawat, Veeranjaneyulu Sadhanala, Afshin Rostamizadeh, Ayan Chakrabarti, Wittawat Jitkrittum, Vladimir Feinberg, Seungyeon Kim, Hrayr Harutyunyan, Nikunj Saunshi, Zachary Nado, Rakesh Shivanna, Sashank J. Reddi, Aditya Krishna Menon, Rohan Anil, Sanjiv Kumar
conference: "Arxiv"
year: 2024
bibkey: rawat2024little
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.18779'}
tags: ['RAG', 'Pre-Training', 'Efficiency and Optimization', 'Training Techniques', 'Tools', 'Ethics and Bias']
---
A primary challenge in large language model (LLM) development is their
onerous pre-training cost. Typically, such pre-training involves optimizing a
self-supervised objective (such as next-token prediction) over a large corpus.
This paper explores a promising paradigm to improve LLM pre-training efficiency
and quality by suitably leveraging a small language model (SLM). In particular,
this paradigm relies on an SLM to both (1) provide soft labels as additional
training supervision, and (2) select a small subset of valuable ("informative"
and "hard") training examples. Put together, this enables an effective transfer
of the SLM's predictive distribution to the LLM, while prioritizing specific
regions of the training data distribution. Empirically, this leads to reduced
LLM training time compared to standard training, while improving the overall
quality. Theoretically, we develop a statistical framework to systematically
study the utility of SLMs in enabling efficient training of high-quality LLMs.
In particular, our framework characterizes how the SLM's seemingly low-quality
supervision can enhance the training of a much more capable LLM. Furthermore,
it also highlights the need for an adaptive utilization of such supervision, by
striking a balance between the bias and variance introduced by the SLM-provided
soft labels. We corroborate our theoretical framework by improving the
pre-training of an LLM with 2.8B parameters by utilizing a smaller LM with 1.5B
parameters on the Pile dataset.
