---
layout: publication
title: 'Transformers Are Universally Consistent'
authors: Sagar Ghosh, Kushal Bose, Swagatam Das
conference: "Arxiv"
year: 2025
bibkey: ghosh2025transformers
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.24531"}
tags: ['Transformer', 'Model Architecture', 'Language Modeling', 'Reinforcement Learning', 'Attention Mechanism', 'Pretraining Methods', 'Prompting', 'In-Context Learning']
---
Despite their central role in the success of foundational models and large-scale language modeling, the theoretical foundations governing the operation of Transformers remain only partially understood. Contemporary research has largely focused on their representational capacity for language comprehension and their prowess in in-context learning, frequently under idealized assumptions such as linearized attention mechanisms. Initially conceived to model sequence-to-sequence transformations, a fundamental and unresolved question is whether Transformers can robustly perform functional regression over sequences of input tokens. This question assumes heightened importance given the inherently non-Euclidean geometry underlying real-world data distributions. In this work, we establish that Transformers equipped with softmax-based nonlinear attention are uniformly consistent when tasked with executing Ordinary Least Squares (OLS) regression, provided both the inputs and outputs are embedded in hyperbolic space. We derive deterministic upper bounds on the empirical error which, in the asymptotic regime, decay at a provable rate of \\(\mathcal\{O\}(t^\{-1/2d\})\\), where \\(t\\) denotes the number of input tokens and \\(d\\) the embedding dimensionality. Notably, our analysis subsumes the Euclidean setting as a special case, recovering analogous convergence guarantees parameterized by the intrinsic dimensionality of the data manifold. These theoretical insights are corroborated through empirical evaluations on real-world datasets involving both continuous and categorical response variables.
