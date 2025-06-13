---
layout: publication
title: 'Probe-free Low-rank Activation Intervention'
authors: Chonghe Jiang, Bao Nguyen, Anthony Man-cho So, Viet Anh Nguyen
conference: "Arxiv"
year: 2025
bibkey: jiang2025probe
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.04043"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Fine-Tuning', 'Attention Mechanism']
---
Language models (LMs) can produce texts that appear accurate and coherent but
contain untruthful or toxic content. Inference-time interventions that edit the
hidden activations have shown promising results in steering the LMs towards
desirable generations. Existing activation intervention methods often comprise
an activation probe to detect undesirable generation, triggering the activation
modification to steer subsequent generation. This paper proposes a probe-free
intervention method FLORAIN for all attention heads in a specific activation
layer. It eliminates the need to train classifiers for probing purposes. The
intervention function is parametrized by a sample-wise nonlinear low-rank
mapping, which is trained by minimizing the distance between the modified
activations and their projection onto the manifold of desirable content. Under
specific constructions of the manifold and projection distance, we show that
the intervention strategy can be computed efficiently by solving a smooth
optimization problem. The empirical results, benchmarked on multiple base
models, demonstrate that FLORAIN consistently outperforms several baseline
methods in enhancing model truthfulness and quality across generation and
multiple-choice tasks.
