---
layout: publication
title: 'Selective Attention Improves Transformer'
authors: Yaniv Leviathan, Matan Kalman, Yossi Matias
conference: "Arxiv"
year: 2024
bibkey: leviathan2024selective
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.02703"}
tags: ['Model Architecture', 'Language Modeling', 'Pretraining Methods', 'Transformer', 'Attention Mechanism']
---
Unneeded elements in the attention's context degrade performance. We
introduce Selective Attention, a simple parameter-free change to the standard
attention mechanism which reduces attention to unneeded elements. Selective
attention consistently improves language modeling and downstream task
performance in a variety of model sizes and context lengths. For example,
transformers trained with the language modeling objective on C4 with selective
attention perform language modeling equivalently to standard transformers with
~2X more heads and parameters in their attention modules. Selective attention
also allows decreasing the size of the attention's context buffer, leading to
meaningful reductions in the memory and compute requirements during inference.
For example, transformers trained on C4 with context sizes of 512, 1,024, and
2,048 need 16X, 25X, and 47X less memory for their attention module,
respectively, when equipped with selective attention, as those without
selective attention, with the same validation perplexity.
