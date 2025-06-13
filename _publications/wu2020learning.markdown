---
layout: publication
title: 'Learning Accurate Integer Transformer Machine-translation Models'
authors: Ephrem Wu
conference: "Arxiv"
year: 2020
bibkey: wu2020learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2001.00926"}
tags: ['Security', 'Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'Pretraining Methods', 'Transformer']
---
We describe a method for training accurate Transformer machine-translation
models to run inference using 8-bit integer (INT8) hardware matrix multipliers,
as opposed to the more costly single-precision floating-point (FP32) hardware.
Unlike previous work, which converted only 85 Transformer matrix
multiplications to INT8, leaving 48 out of 133 of them in FP32 because of
unacceptable accuracy loss, we convert them all to INT8 without compromising
accuracy. Tested on the newstest2014 English-to-German translation task, our
INT8 Transformer Base and Transformer Big models yield BLEU scores that are
99.3% to 100% relative to those of the corresponding FP32 models. Our approach
converts all matrix-multiplication tensors from an existing FP32 model into
INT8 tensors by automatically making range-precision trade-offs during
training. To demonstrate the robustness of this approach, we also include
results from INT6 Transformer models.
