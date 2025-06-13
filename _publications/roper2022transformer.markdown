---
layout: publication
title: 'Transformer-based Program Synthesis For Low-data Environments'
authors: Jack Roper
conference: "Arxiv"
year: 2022
bibkey: roper2022transformer
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2205.09246'}
tags: ['Transformer', 'GPT', 'Model Architecture', 'Reinforcement Learning', 'Pretraining Methods']
---
Recent advancements in large pre-trained transformer models (GPT2/3, T5) have
found use in program synthesis to generate programs that satisfy a set of
input/output examples. However, these models perform poorly on long-horizon and
low-data tasks, and often don't seem to understand the semantics of the
languages they generate. We investigate an approach that tackles both of these
issues, by using attributed context-free-grammars of programming languages to
generate programs, and then analyzing generated programs so that they can be
annotated with compile and runtime attributes, such as types, so that
information about the program can be remembered during long-horizon generation.
We firstly find that synthesized datasets can be made efficiently and can
provide transformer models with enough data in order to perform well on some
synthesis tasks. We also find that giving models access to program attributes
is especially effective in low-data environments, and tends improve the quality
and reduce errors of transformer-generated programs.
