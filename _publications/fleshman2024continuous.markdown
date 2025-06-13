---
layout: publication
title: 'Adapterswap: Continuous Training Of Llms With Data Removal And Access-control Guarantees'
authors: William Fleshman, Aleem Khan, Marc Marone, Benjamin Van Durme
conference: "Arxiv"
year: 2024
bibkey: fleshman2024continuous
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2404.08417'}
tags: ['Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
Large language models (LLMs) are increasingly capable of completing knowledge
intensive tasks by recalling information from a static pretraining corpus. Here
we are concerned with LLMs in the context of evolving data requirements. For
instance: batches of new data that are introduced periodically; subsets of data
with user-based access controls; or requirements on dynamic removal of
documents with guarantees that associated knowledge cannot be recalled. We wish
to satisfy these requirements while at the same time ensuring a model does not
forget old information when new data becomes available. To address these
issues, we introduce AdapterSwap, a training and inference scheme that
organizes knowledge from a data collection into a set of low-rank adapters,
which are dynamically composed during inference. Our experiments demonstrate
AdapterSwap's ability to support efficient continual learning, while also
enabling organizations to have fine-grained control over data access and
deletion.
