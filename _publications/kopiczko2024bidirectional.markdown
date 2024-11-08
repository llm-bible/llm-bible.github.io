---
layout: publication
title: 'Bitune: Bidirectional Instruction-tuning'
authors: Kopiczko Dawid J., Blankevoort Tijmen, Asano Yuki M.
conference: "Arxiv"
year: 2024
bibkey: kopiczko2024bidirectional
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.14862"}
tags: ['Attention Mechanism', 'Fine Tuning', 'Model Architecture', 'Prompting', 'RAG']
---
We introduce Bitune, a method that improves instruction-tuning of pretrained
decoder-only large language models, leading to consistent gains on downstream
tasks. Bitune applies both causal and bidirectional attention to the prompt, to
obtain a better representation of the query or instruction. We realize this by
introducing two sets of parameters, for which we apply parameter-efficient
finetuning techniques. These causal and bidirectional features are then
combined into a weighted average with trainable coefficients, which is
subsequently used to generate new tokens. We demonstrate significant
improvements in zero-shot performance on commonsense reasoning, arithmetic, and
language understanding tasks, while extensive ablation studies validate the
role of each component and demonstrate the method's agnosticism to different
PEFT techniques.
