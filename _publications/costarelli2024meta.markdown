---
layout: publication
title: 'Meta-models: An Architecture For Decoding LLM Behaviors Through Interpreted Embeddings And Natural Language'
authors: Anthony Costarelli, Mat Allen, Severin Field
conference: "Arxiv"
year: 2024
bibkey: costarelli2024meta
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.02472"}
  - {name: "Code", url: "https://github.com/acostarelli/meta-models-public"}
tags: ['Interpretability and Explainability', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Has Code']
---
As Large Language Models (LLMs) become increasingly integrated into our daily
lives, the potential harms from deceptive behavior underlie the need for
faithfully interpreting their decision-making. While traditional probing
methods have shown some effectiveness, they remain best for narrowly scoped
tasks while more comprehensive explanations are still necessary. To this end,
we investigate meta-models-an architecture using a "meta-model" that takes
activations from an "input-model" and answers natural language questions about
the input-model's behaviors. We evaluate the meta-model's ability to generalize
by training them on selected task types and assessing their out-of-distribution
performance in deceptive scenarios. Our findings show that meta-models
generalize well to out-of-distribution tasks and point towards opportunities
for future research in this area. Our code is available at
https://github.com/acostarelli/meta-models-public .
