---
layout: publication
title: SSD45;LM Semi45;autoregressive Simplex45;based Diffusion Language Model For Text Generation And Modular Control
authors: Han Xiaochuang, Kumar Sachin, Tsvetkov Yulia
conference: "Arxiv"
year: 2022
bibkey: han2022ssd
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.17432"}
tags: ['Applications', 'GPT', 'Language Modeling', 'Merging', 'Model Architecture', 'Pretraining Methods']
---
Despite the growing success of diffusion models in continuous45;valued domains (e.g. images) similar efforts for discrete domains such as text have yet to match the performance of autoregressive language models. In this work we present SSD45;LM 45;45; a diffusion45;based language model with two key design choices. First SSD45;LM is semi45;autoregressive iteratively generating blocks of text allowing for flexible output length at decoding time while enabling local bidirectional context updates. Second it is simplex45;based performing diffusion on the natural vocabulary space rather than a learned latent space allowing us to incorporate classifier guidance and modular control using off45;the45;shelf classifiers without any adaptation. We evaluate SSD45;LM on unconstrained text generation benchmarks and show that it matches or outperforms strong autoregressive GPT45;2 models across standard quality and diversity metrics while vastly outperforming diffusion45;based baselines. On controlled text generation SSD45;LM also outperforms competitive baselines with an extra advantage in modularity.
