---
layout: publication
title: 'Universal Length Generalization With Turing Programs'
authors: Kaiying Hou, David Brandfonbrener, Sham Kakade, Samy Jelassi, Eran Malach
conference: "Arxiv"
year: 2024
bibkey: hou2024universal
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2407.03310'}
tags: ['Transformer', 'Training Techniques', 'Model Architecture', 'Tools', 'Pretraining Methods']
---
Length generalization refers to the ability to extrapolate from short
training sequences to long test sequences and is a challenge for current large
language models. While prior work has proposed some architecture or data format
changes to achieve length generalization, these proposals typically apply to a
limited set of tasks. Building on prior scratchpad and Chain-of-Thought (CoT)
techniques, we propose Turing Programs, a novel CoT strategy that decomposes an
algorithmic task into steps mimicking the computation of a Turing Machine. This
framework is both universal, as it can accommodate any algorithmic task, and
simple, requiring only copying text from the context with small modifications.
We show that by using Turing Programs, we obtain robust length generalization
on a range of algorithmic tasks: addition, multiplication and in-context SGD.
We then demonstrate that transformers achieve length generalization on random
Turing Programs, suggesting that length generalization is possible for any
algorithmic task. Finally, we theoretically prove that transformers can
implement Turing Programs, constructing a simple RASP (Weiss et al.) program
that simulates an arbitrary Turing machine.
