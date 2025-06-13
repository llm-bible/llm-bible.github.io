---
layout: publication
title: 'Balancing Speed And Stability: The Trade-offs Of FP8 Vs. BF16 Training In Llms'
authors: Kazuki Fujii, Taishi Nakamura, Rio Yokota
conference: "Arxiv"
year: 2024
bibkey: fujii2024balancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.08719"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'Attention Mechanism']
---
Large Language Models (LLMs) have attracted significant attention due to
their human-like language understanding and generation capabilities, as well as
their applicability across various domains.
  These models, characterized by their massive scale and extensive training
data, continue to push the boundaries of what is possible in natural language
processing. The Llama 3 series, for instance, exemplifies this trend with its
flagship model boasting 405 billion parameters trained on 15.6 trillion tokens.
The immense computational demands associated with training such models have
spurred ongoing research into optimizing the efficiency of the training
process, particularly through the use of lower-precision formats.
  NVIDIA's H100 GPU, which introduces support for FP8 in addition to the more
conventional FP16 and BF16 formats, has emerged as a focal point in this
optimization effort. Preliminary studies suggest that FP8 could offer
substantial reductions in training time without sacrificing model performance
when compared to BF16, making it a promising candidate for large-scale model
training. However, the broader implications of adopting FP8, particularly in
terms of training stability and downstream task performance, have yet to be
fully understood.
  In this study, we delve into the practical trade-offs involved in adopting
FP8 over BF16 for training LLMs.
