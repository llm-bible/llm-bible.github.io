---
layout: publication
title: 'Associative Memory Inspires Improvements For In-context Learning Using A Novel Attention Residual Stream Architecture'
authors: Thomas F Burns, Tomoki Fukai, Christopher J Earls
conference: "Arxiv"
year: 2024
bibkey: burns2024associative
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.15113"}
tags: ['Transformer', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods', 'Prompting', 'In-Context Learning']
---
Large language models (LLMs) demonstrate an impressive ability to utilise
information within the context of their input sequences to appropriately
respond to data unseen by the LLM during its training procedure. This ability
is known as in-context learning (ICL). Humans and non-human animals demonstrate
similar abilities, however their neural architectures differ substantially from
LLMs. Despite this, a critical component within LLMs, the attention mechanism,
resembles modern associative memory models, widely used in and influenced by
the computational neuroscience community to model biological memory systems.
Using this connection, we introduce an associative memory model capable of
performing ICL. We use this as inspiration for a novel residual stream
architecture which allows information to directly flow between attention heads.
We test this architecture during training within a two-layer Transformer and
show its ICL abilities manifest more quickly than without this modification. We
then apply our architecture in small language models with 8 million parameters,
focusing on attention head values, with results also indicating improved ICL
performance at this larger and more naturalistic scale.
