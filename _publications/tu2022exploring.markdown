---
layout: publication
title: 'Adavae: Exploring Adaptive Gpt-2s In Variational Auto-encoders For Language Modeling'
authors: Tu Haoqin, Yang Zhongliang, Yang Jinshuai, Huang Yongfeng
conference: "Arxiv"
year: 2022
bibkey: tu2022exploring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2205.05862"}
  - {name: "Code", url: "https://github.com/ImKeTT/AdaVAE"}
tags: ['Applications', 'Attention Mechanism', 'GPT', 'Has Code', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Tools', 'Training Techniques', 'Transformer']
---
Variational Auto-Encoder (VAE) has become the de-facto learning paradigm in
achieving representation learning and generation for natural language at the
same time. Nevertheless, existing VAE-based language models either employ
elementary RNNs, which is not powerful to handle complex works in the
multi-task situation, or fine-tunes two pre-trained language models (PLMs) for
any downstream task, which is a huge drain on resources. In this paper, we
propose the first VAE framework empowered with adaptive GPT-2s (AdaVAE).
Different from existing systems, we unify both the encoder\&decoder of the VAE
model using GPT-2s with adaptive parameter-efficient components, and further
introduce Latent Attention operation to better construct latent space from
transformer models. Experiments from multiple dimensions validate that AdaVAE
is competent to effectively organize language in three related tasks (language
modeling, representation modeling and guided text generation) even with less
than \\(15\%\\) activated parameters in training. Our code is available at
\url\{https://github.com/ImKeTT/AdaVAE\}.
