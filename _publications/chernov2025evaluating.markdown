---
layout: publication
title: 'Evaluating Expert Contributions In A Moe LLM For Quiz-based Tasks'
authors: Andrei Chernov
conference: "Arxiv"
year: 2025
bibkey: chernov2025evaluating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.17187"}
tags: ['RAG', 'Model Architecture', 'Attention Mechanism']
---
Recently, Large Language Models (LLMs) with Mixture of Experts (MoE) layers
have gained significant attention. Currently, state-of-the-art LLMs utilize
this architecture. There is a substantial amount of research on how to train
such models and how to select hyperparameters for this architecture. However,
there is a lack of studies focusing on post-evaluation analysis of MoE layer
properties. In this paper, we take a first step toward closing this gap by
evaluating expert contributions on the quiz-based MMLU benchmark. We show that
most experts were never activated during inference on this benchmark.
Additionally, the output distribution of gating networks is much closer to
uniform than sparse. Finally, we demonstrate that the average performance of
some experts within the same layer varies significantly.
