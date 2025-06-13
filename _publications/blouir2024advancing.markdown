---
layout: publication
title: 'Birdie: Advancing State Space Models With Reward-driven Objectives And Curricula'
authors: Sam Blouir, Jimmy T. H. Smith, Antonios Anastasopoulos, Amarda Shehu
conference: "Arxiv"
year: 2024
bibkey: blouir2024advancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.01030"}
  - {name: "Code", url: "https://www.github.com/samblouir/birdie,"}
tags: ['Transformer', 'Pre-Training', 'Agentic', 'Efficiency and Optimization', 'Applications', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Attention Mechanism', 'Has Code', 'Pretraining Methods']
---
Efficient state space models (SSMs), such as linear recurrent neural networks
and linear attention variants, offer computational advantages over Transformers
but struggle with tasks requiring long-range in-context retrieval-like text
copying, associative recall, and question answering over long contexts.
Previous efforts to address these challenges have focused on architectural
modifications, often reintroducing computational inefficiencies. In this paper,
we propose a novel training procedure, Birdie, that significantly enhances the
in-context retrieval capabilities of SSMs without altering their architecture.
Our approach combines bidirectional input processing with dynamic mixtures of
specialized pre-training objectives, optimized via reinforcement learning. We
introduce a new bidirectional SSM architecture that seamlessly transitions from
bidirectional context processing to causal generation. Experimental evaluations
demonstrate that Birdie markedly improves performance on retrieval-intensive
tasks such as multi-number phone book lookup, long paragraph
question-answering, and infilling. This narrows the performance gap with
Transformers, while retaining computational efficiency. Our findings highlight
the importance of training procedures in leveraging the fixed-state capacity of
SSMs, offering a new direction to advance their capabilities. All code and
pre-trained models are available at https://www.github.com/samblouir/birdie,
with support for JAX and PyTorch.
