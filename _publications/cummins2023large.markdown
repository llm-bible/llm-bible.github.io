---
layout: publication
title: 'Large Language Models For Compiler Optimization'
authors: Chris Cummins, Volker Seeker, Dejan Grubisic, Mostafa Elhoushi, Youwei Liang, Baptiste Roziere, Jonas Gehring, Fabian Gloeckle, Kim Hazelwood, Gabriel Synnaeve, Hugh Leather
conference: "Arxiv"
year: 2023
bibkey: cummins2023large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.07062"}
tags: ['Transformer', 'Efficiency and Optimization', 'Model Architecture', 'Training Techniques', 'Pretraining Methods']
---
We explore the novel application of Large Language Models to code
optimization. We present a 7B-parameter transformer model trained from scratch
to optimize LLVM assembly for code size. The model takes as input unoptimized
assembly and outputs a list of compiler options to best optimize the program.
Crucially, during training, we ask the model to predict the instruction counts
before and after optimization, and the optimized code itself. These auxiliary
learning tasks significantly improve the optimization performance of the model
and improve the model's depth of understanding.
  We evaluate on a large suite of test programs. Our approach achieves a 3.0%
improvement in reducing instruction counts over the compiler, outperforming two
state-of-the-art baselines that require thousands of compilations. Furthermore,
the model shows surprisingly strong code reasoning abilities, generating
compilable code 91% of the time and perfectly emulating the output of the
compiler 70% of the time.
