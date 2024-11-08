---
layout: publication
title: 'Synergy-of-thoughts: Eliciting Efficient Reasoning In Hybrid Language Models'
authors: Shang Yu, Li Yu, Xu Fengli, Li Yong
conference: "Arxiv"
year: 2024
bibkey: shang2024synergy
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.02563"}
tags: ['RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Large language models (LLMs) have shown impressive emergent abilities in a
wide range of tasks, but the associated expensive API cost greatly limits the
real application. Previous works like chain-of-thought (CoT) and
tree-of-thoughts (ToT) have predominately focused on enhancing accuracy, but
overlook the rapidly increasing API cost, which could be particularly
problematic for open-ended real-world tasks with huge solution spaces.
Motivated by the dual process theory of human cognition, we propose "Synergy of
Thoughts"(SoT) to unleash the synergistic potential of hybrid LLMs with
different scales for efficient reasoning. By default, SoT uses smaller-scale
language models to generate multiple low-cost intuitive thoughts, which
resembles the parallel intuitions produced by System 1. We then design a
confidence evaluator where the intuitive thoughts are cross-evaluated and
introduce a controllable threshold mechanism to decide their mutual conflict.
If these intuitive thoughts exhibit conflicts, SoT will invoke the reflective
reasoning of scaled-up language models to emulate the intervention of System 2,
which will override the intuitive thoughts and rectify the reasoning results.
This framework is model-agnostic and training-free, which can be flexibly
implemented with various off-the-shelf LLMs. Experiments on six representative
reasoning tasks show that SoT substantially reduces the API cost by
38.3%-75.1%, and simultaneously achieves state-of-the-art reasoning accuracy
and solution diversity. Notably, the average token cost reduction on open-ended
tasks reaches up to 69.1%.
