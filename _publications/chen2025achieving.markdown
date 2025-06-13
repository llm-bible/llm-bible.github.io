---
layout: publication
title: 'Achieving More With Less: Additive Prompt Tuning For Rehearsal-free Class-incremental Learning'
authors: Haoran Chen, Ping Wang, Zihan Zhou, Xu Zhang, Zuxuan Wu, Yu-gang Jiang
conference: "Arxiv"
year: 2025
bibkey: chen2025achieving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.07979"}
tags: ['Fine-Tuning', 'Tools', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods', 'Prompting']
---
Class-incremental learning (CIL) enables models to learn new classes
progressively while preserving knowledge of previously learned ones. Recent
advances in this field have shifted towards parameter-efficient fine-tuning
techniques, with many approaches building upon the framework that maintains a
pool of learnable prompts. Although effective, these methods introduce
substantial computational overhead, primarily due to prompt pool querying and
increased input sequence lengths from prompt concatenation. In this work, we
present a novel prompt-based approach that addresses this limitation. Our
method trains a single set of shared prompts across all tasks and, rather than
concatenating prompts to the input, directly modifies the CLS token's attention
computation by adding the prompts to it. This simple and lightweight design not
only significantly reduces computational complexity-both in terms of inference
costs and the number of trainable parameters-but also eliminates the need to
optimize prompt lengths for different downstream tasks, offering a more
efficient yet powerful solution for rehearsal-free class-incremental learning.
Extensive experiments across a diverse range of CIL benchmarks demonstrate the
effectiveness of our approach, highlighting its potential to establish a new
prompt-based CIL paradigm. Furthermore, experiments on general recognition
benchmarks beyond the CIL setting also show strong performance, positioning our
method as a promising candidate for a general parameter-efficient fine-tuning
approach.
