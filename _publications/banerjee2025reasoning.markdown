---
layout: publication
title: 'CRANE: Reasoning With Constrained LLM Generation'
authors: Debangshu Banerjee, Tarun Suresh, Shubham Ugare, Sasa Misailovic, Gagandeep Singh
conference: "Arxiv"
year: 2025
bibkey: banerjee2025reasoning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.09061"}
tags: ['Training Techniques', 'Applications', 'Interpretability and Explainability']
---
Code generation, symbolic math reasoning, and other tasks require LLMs to
produce outputs that are both syntactically and semantically correct.
Constrained LLM generation is a promising direction to enforce adherence to
formal grammar, but prior works have empirically observed that strict
enforcement of formal constraints often diminishes the reasoning capabilities
of LLMs. In this work, we first provide a theoretical explanation for why
constraining LLM outputs to very restrictive grammars that only allow
syntactically valid final answers reduces the reasoning capabilities of the
model. Second, we demonstrate that by augmenting the output grammar with
carefully designed additional rules, it is always possible to preserve the
reasoning capabilities of the LLM while ensuring syntactic and semantic
correctness in its outputs. Building on these theoretical insights, we propose
a reasoning-augmented constrained decoding algorithm, CRANE, which effectively
balances the correctness of constrained generation with the flexibility of
unconstrained generation. Experiments on multiple open-source LLMs and
benchmarks show that CRANE significantly outperforms both state-of-the-art
constrained decoding strategies and standard unconstrained decoding, showing up
to 10% points accuracy improvement over baselines on challenging symbolic
reasoning benchmarks GSM-symbolic and FOLIO.
