---
layout: publication
title: 'Scalable Language Models With Posterior Inference Of Latent Thought Vectors'
authors: Deqian Kong, Minglu Zhao, Dehong Xu, Bo Pang, Shu Wang, Edouardo Honig, Zhangzhang Si, Chuan Li, Jianwen Xie, Sirui Xie, Ying Nian Wu
conference: "Arxiv"
year: 2025
bibkey: kong2025scalable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.01567"}
tags: ['Transformer', 'Tools', 'GPT', 'Efficiency and Optimization', 'Applications', 'Model Architecture', 'Language Modeling', 'Merging', 'Training Techniques', 'Pretraining Methods', 'Few-Shot']
---
We propose a novel family of language models, Latent-Thought Language Models
(LTMs), which incorporate explicit latent thought vectors that follow an
explicit prior model in latent space. These latent thought vectors guide the
autoregressive generation of ground tokens through a Transformer decoder.
Training employs a dual-rate optimization process within the classical
variational Bayes framework: fast learning of local variational parameters for
the posterior distribution of latent vectors, and slow learning of global
decoder parameters. Empirical studies reveal that LTMs possess additional
scaling dimensions beyond traditional LLMs, yielding a structured design space.
Higher sample efficiency can be achieved by increasing training compute per
token, with further gains possible by trading model size for more inference
steps. Designed based on these scaling properties, LTMs demonstrate superior
sample and parameter efficiency compared to conventional autoregressive models
and discrete diffusion models. They significantly outperform these counterparts
in validation perplexity and zero-shot language modeling. Additionally, LTMs
exhibit emergent few-shot in-context reasoning capabilities that scale with
model and latent size, and achieve competitive performance in conditional and
unconditional text generation.
