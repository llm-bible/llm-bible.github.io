---
layout: publication
title: 'Moin: Mixture Of Introvert Experts To Upcycle An LLM'
authors: Ajinkya Tejankar, Kl Navaneet, Ujjawal Panchal, Kossar Pourahmadi, Hamed Pirsiavash
conference: "Arxiv"
year: 2024
bibkey: tejankar2024mixture
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.09687"}
tags: ['Training Techniques', 'Pre-Training', 'Reinforcement Learning']
---
The goal of this paper is to improve (upcycle) an existing large language
model without the prohibitive requirements of continued pre-training of the
full-model. The idea is to split the pre-training data into semantically
relevant groups and train an expert on each subset. An expert takes the form of
a lightweight adapter added on the top of a frozen base model. During
inference, an incoming query is first routed to the most relevant expert which
is then loaded onto the base model for the forward pass. Unlike typical Mixture
of Experts (MoE) models, the experts in our method do not work with other
experts for a single query. Hence, we dub them "introvert" experts. Freezing
the base model and keeping the experts as lightweight adapters allows extreme
parallelism during training and inference. Training of all experts can be done
in parallel without any communication channels between them. Similarly, the
inference can also be heavily parallelized by distributing experts on different
GPUs and routing each request to the GPU containing its relevant expert. We
implement a proof-of-concept version of this method and show the validity of
our approach.
