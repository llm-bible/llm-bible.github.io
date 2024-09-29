---
layout: publication
title: Edgebert Sentence45;level Energy Optimizations For Latency45;aware Multi45;task NLP Inference
authors: Tambe Thierry, Hooper Coleman, Pentecost Lillian, Jia Tianyu, Yang En-yu, Donato Marco, Sanh Victor, Whatmough Paul N., Rush Alexander M., Brooks David, Wei Gu-yeon
conference: "Arxiv"
year: 2020
bibkey: tambe2020sentence
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2011.14203"}
tags: ['Attention Mechanism', 'BERT', 'Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Pruning', 'Quantization', 'Reinforcement Learning', 'Tools', 'Transformer']
---
Transformer45;based language models such as BERT provide significant accuracy improvement for a multitude of natural language processing (NLP) tasks. However their hefty computational and memory demands make them challenging to deploy to resource45;constrained edge platforms with strict latency requirements. We present EdgeBERT an in45;depth algorithm45;hardware co45;design for latency45;aware energy optimization for multi45;task NLP. EdgeBERT employs entropy45;based early exit predication in order to perform dynamic voltage45;frequency scaling (DVFS) at a sentence granularity for minimal energy consumption while adhering to a prescribed target latency. Computation and memory footprint overheads are further alleviated by employing a calibrated combination of adaptive attention span selective network pruning and floating45;point quantization. Furthermore in order to maximize the synergistic benefits of these algorithms in always45;on and intermediate edge computing settings we specialize a 12nm scalable hardware accelerator system integrating a fast45;switching low45;dropout voltage regulator (LDO) an all45;digital phase45;locked loop (ADPLL) as well as high45;density embedded non45;volatile memories (eNVMs) wherein the sparse floating45;point bit encodings of the shared multi45;task parameters are carefully stored. Altogether latency45;aware multi45;task NLP inference acceleration on the EdgeBERT hardware system generates up to 7x 2.5x and 53x lower energy compared to the conventional inference without early stopping the latency45;unbounded early exit approach and CUDA adaptations on an Nvidia Jetson Tegra X2 mobile GPU respectively.
