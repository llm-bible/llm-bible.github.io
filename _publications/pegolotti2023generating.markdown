---
layout: publication
title: 'Qigen: Generating Efficient Kernels For Quantized Inference On Large Language Models'
authors: Tommaso Pegolotti, Elias Frantar, Dan Alistarh, Markus Püschel
conference: "Arxiv"
year: 2023
bibkey: pegolotti2023generating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2307.03738'}
  - {name: "Code", url: 'https://github.com/IST-DASLab/QIGen'}
tags: ['Reinforcement Learning', 'Has Code', 'Applications', 'Model Architecture']
---
We present ongoing work on a new automatic code generation approach for
supporting quantized generative inference on LLMs such as LLaMA or OPT on
off-the-shelf CPUs. Our approach is informed by the target architecture and a
performance model, including both hardware characteristics and method-specific
accuracy constraints. Results on CPU-based inference for LLaMA models show that
our approach can lead to high performance and high accuracy, comparing
favorably to the best existing open-source solution. A preliminary
implementation is available at https://github.com/IST-DASLab/QIGen.
