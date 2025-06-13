---
layout: publication
title: 'Minif2f In Rocq: Automatic Translation Between Proof Assistants -- A Case Study'
authors: Jules Viennot, Guillaume Baudart, Emilio Jesùs Gallego Arias, Marc Lelarge
conference: "Arxiv"
year: 2025
bibkey: viennot2025automatic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.04763"}
  - {name: "Code", url: "https://github.com/LLM4Rocq/miniF2F-rocq"}
tags: ['Prompting', 'Model Architecture', 'GPT', 'Has Code']
---
In this work, we conduct an experiment using state-of-the-art LLMs to
translate MiniF2F into Rocq. The translation task focuses on generating a Rocq
theorem based on three sources: a natural language description, the Lean
formalization, and the Isabelle formalization. We conducted our experiment in 3
stages of increasing complexity, from basic one-shot prompting to multi-turn
conversations that incorporate feedback from unsuccessful attempts. At each
stage, we perform multiple rounds of translation using increasingly advanced
models: GPT-4o mini, Claude 3.5 Sonnet, o1 mini, and o1. We successfully
translated 478 out of 488 theorems. The dataset is opensource:
https://github.com/LLM4Rocq/miniF2F-rocq.
