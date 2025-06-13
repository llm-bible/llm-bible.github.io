---
layout: publication
title: 'Library Learning Doesn''t: The Curious Case Of The Single-use "library"'
authors: Ian Berlot-attwell, Frank Rudzicz, Xujie Si
conference: "Arxiv"
year: 2024
bibkey: berlotattwell2024library
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.20274'}
  - {name: "Code", url: 'https://github.com/ikb-a/curious-case'}
tags: ['Has Code', 'Tools']
---
Advances in Large Language Models (LLMs) have spurred a wave of LLM library
learning systems for mathematical reasoning. These systems aim to learn a
reusable library of tools, such as formal Isabelle lemmas or Python programs
that are tailored to a family of tasks. Many of these systems are inspired by
the human structuring of knowledge into reusable and extendable concepts, but
do current methods actually learn reusable libraries of tools?
  We study two library learning systems for mathematics which both reported
increased accuracy: LEGO-Prover and TroVE. We find that function reuse is
extremely infrequent on miniF2F and MATH. Our followup ablation experiments
suggest that, rather than reuse, self-correction and self-consistency are the
primary drivers of the observed performance gains. Our code and data are
available at https://github.com/ikb-a/curious-case
