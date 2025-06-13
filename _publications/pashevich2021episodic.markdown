---
layout: publication
title: 'Episodic Transformer For Vision-and-language Navigation'
authors: Alexander Pashevich, Cordelia Schmid, Chen Sun
conference: "Arxiv"
year: 2021
bibkey: pashevich2021episodic
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2105.06453'}
tags: ['Agentic', 'Transformer', 'RAG', 'Training Techniques', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods']
---
Interaction and navigation defined by natural language instructions in
dynamic environments pose significant challenges for neural agents. This paper
focuses on addressing two challenges: handling long sequence of subtasks, and
understanding complex human instructions. We propose Episodic Transformer
(E.T.), a multimodal transformer that encodes language inputs and the full
episode history of visual observations and actions. To improve training, we
leverage synthetic instructions as an intermediate representation that
decouples understanding the visual appearance of an environment from the
variations of natural language instructions. We demonstrate that encoding the
history with a transformer is critical to solve compositional tasks, and that
pretraining and joint training with synthetic instructions further improve the
performance. Our approach sets a new state of the art on the challenging ALFRED
benchmark, achieving 38.4% and 8.5% task success rates on seen and unseen test
splits.
