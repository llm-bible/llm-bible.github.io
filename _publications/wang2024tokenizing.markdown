---
layout: publication
title: 'LARP: Tokenizing Videos With A Learned Autoregressive Generative Prior'
authors: Hanyu Wang, Saksham Suri, Yixuan Ren, Hao Chen, Abhinav Shrivastava
conference: "Arxiv"
year: 2024
bibkey: wang2024tokenizing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.21264'}
tags: ['Transformer', 'Training Techniques', 'Model Architecture', 'GPT', 'Multimodal Models', 'Reinforcement Learning', 'Tokenization', 'Pretraining Methods']
---
We present LARP, a novel video tokenizer designed to overcome limitations in
current video tokenization methods for autoregressive (AR) generative models.
Unlike traditional patchwise tokenizers that directly encode local visual
patches into discrete tokens, LARP introduces a holistic tokenization scheme
that gathers information from the visual content using a set of learned
holistic queries. This design allows LARP to capture more global and semantic
representations, rather than being limited to local patch-level information.
Furthermore, it offers flexibility by supporting an arbitrary number of
discrete tokens, enabling adaptive and efficient tokenization based on the
specific requirements of the task. To align the discrete token space with
downstream AR generation tasks, LARP integrates a lightweight AR transformer as
a training-time prior model that predicts the next token on its discrete latent
space. By incorporating the prior model during training, LARP learns a latent
space that is not only optimized for video reconstruction but is also
structured in a way that is more conducive to autoregressive generation.
Moreover, this process defines a sequential order for the discrete tokens,
progressively pushing them toward an optimal configuration during training,
ensuring smoother and more accurate AR generation at inference time.
Comprehensive experiments demonstrate LARP's strong performance, achieving
state-of-the-art FVD on the UCF101 class-conditional video generation
benchmark. LARP enhances the compatibility of AR models with videos and opens
up the potential to build unified high-fidelity multimodal large language
models (MLLMs).
