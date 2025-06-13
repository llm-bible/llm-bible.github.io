---
layout: publication
title: 'Proto: Program-guided Transformer For Program-guided Tasks'
authors: Zelin Zhao, Karan Samel, Binghong Chen, Le Song
conference: "Arxiv"
year: 2021
bibkey: zhao2021program
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2110.00804'}
tags: ['Attention Mechanism', 'Agentic', 'Transformer', 'RAG', 'Model Architecture', 'Interpretability', 'Pretraining Methods']
---
Programs, consisting of semantic and structural information, play an
important role in the communication between humans and agents. Towards learning
general program executors to unify perception, reasoning, and decision making,
we formulate program-guided tasks which require learning to execute a given
program on the observed task specification. Furthermore, we propose the
Program-guided Transformer (ProTo), which integrates both semantic and
structural guidance of a program by leveraging cross-attention and masked
self-attention to pass messages between the specification and routines in the
program. ProTo executes a program in a learned latent space and enjoys stronger
representation ability than previous neural-symbolic approaches. We demonstrate
that ProTo significantly outperforms the previous state-of-the-art methods on
GQA visual reasoning and 2D Minecraft policy learning datasets. Additionally,
ProTo demonstrates better generalization to unseen, complex, and human-written
programs.
