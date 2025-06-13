---
layout: publication
title: 'Scaling FP8 Training To Trillion-token Llms'
authors: Maxim Fishman, Brian Chmiel, Ron Banner, Daniel Soudry
conference: "Arxiv"
year: 2024
bibkey: fishman2024scaling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.12517"}
  - {name: "Code", url: "https://github.com/Anonymous1252022/Megatron-DeepSpeed"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Reinforcement Learning', 'Quantization', 'Fine-Tuning', 'Has Code']
---
We train, for the first time, large language models using FP8 precision on
datasets up to 2 trillion tokens -- a 20-fold increase over previous limits.
Through these extended training runs, we uncover critical instabilities in FP8
training that were not observable in earlier works with shorter durations. We
trace these instabilities to outlier amplification by the SwiGLU activation
function. Interestingly, we show, both analytically and empirically, that this
amplification happens only over prolonged training periods, and link it to a
SwiGLU weight alignment process. To address this newly identified issue, we
introduce Smooth-SwiGLU, a novel modification that ensures stable FP8 training
without altering function behavior. We also demonstrate, for the first time,
FP8 quantization of both Adam optimizer moments. Combining these innovations,
we successfully train a 7B parameter model using FP8 precision on 256 Intel
Gaudi2 accelerators, achieving on-par results with the BF16 baseline while
delivering up to a \\(\sim 34 %\\) throughput improvement. A reference
implementation is supplied in
https://github.com/Anonymous1252022/Megatron-DeepSpeed.
