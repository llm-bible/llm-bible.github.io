---
layout: publication
title: SSD-LM\: Semi-autoregressive Simplex-based Diffusion Language Model For Text Generation And Modular Control
authors: Han Xiaochuang, Kumar Sachin, Tsvetkov Yulia
conference: "Arxiv"
year: 2022
bibkey: han2022ssd
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.17432"}
tags: ['Applications', 'GPT', 'Language Modeling', 'Merging', 'Model Architecture', 'Pretraining Methods']
---
Despite the growing success of diffusion models in continuous-valued domains (e.g. images) similar efforts for discrete domains such as text have yet to match the performance of autoregressive language models. In this work we present SSD-LM -- a diffusion-based language model with two key design choices. First SSD-LM is semi-autoregressive iteratively generating blocks of text allowing for flexible output length at decoding time while enabling local bidirectional context updates. Second it is simplex-based performing diffusion on the natural vocabulary space rather than a learned latent space allowing us to incorporate classifier guidance and modular control using off-the-shelf classifiers without any adaptation. We evaluate SSD-LM on unconstrained text generation benchmarks and show that it matches or outperforms strong autoregressive GPT-2 models across standard quality and diversity metrics while vastly outperforming diffusion-based baselines. On controlled text generation SSD-LM also outperforms competitive baselines with an extra advantage in modularity.
