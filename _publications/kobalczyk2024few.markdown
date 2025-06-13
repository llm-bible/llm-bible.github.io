---
layout: publication
title: 'Few-shot Steerable Alignment: Adapting Rewards And LLM Policies With Neural Processes'
authors: Katarzyna Kobalczyk, Claudio Fanconi, Hao Sun, Mihaela Van Der Schaar
conference: "Arxiv"
year: 2024
bibkey: kobalczyk2024few
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.13998"}
  - {name: "Code", url: "https://github.com/kasia-kobalczyk/few-shot-steerable-alignment"}
tags: ['Training Techniques', 'Few-Shot', 'Tools', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning', 'Has Code', 'Applications']
---
As large language models (LLMs) become increasingly embedded in everyday
applications, ensuring their alignment with the diverse preferences of
individual users has become a critical challenge. Currently deployed approaches
typically assume homogeneous user objectives and rely on single-objective
fine-tuning. However, human preferences are inherently heterogeneous,
influenced by various unobservable factors, leading to conflicting signals in
preference data. Existing solutions addressing this diversity often require
costly datasets labelled for specific objectives and involve training multiple
reward models or LLM policies, which is computationally expensive and
impractical. In this work, we present a novel framework for few-shot steerable
alignment, where users' underlying preferences are inferred from a small sample
of their choices. To achieve this, we extend the Bradley-Terry-Luce model to
handle heterogeneous preferences with unobserved variability factors and
propose its practical implementation for reward modelling and LLM fine-tuning.
Thanks to our proposed approach of functional parameter-space conditioning,
LLMs trained with our framework can be adapted to individual preferences at
inference time, generating outputs over a continuum of behavioural modes. We
empirically validate the effectiveness of methods, demonstrating their ability
to capture and align with diverse human preferences in a data-efficient manner.
Our code is made available at:
https://github.com/kasia-kobalczyk/few-shot-steerable-alignment.
