---
layout: publication
title: 'The Best Of Both Worlds: Integrating Language Models And Diffusion Models For Video Generation'
authors: Aoxiong Yin, Kai Shen, Yichong Leng, Xu Tan, Xinyu Zhou, Juncheng Li, Siliang Tang
conference: "Arxiv"
year: 2025
bibkey: yin2025best
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.04606'}
tags: ['GPT', 'Tools', 'Model Architecture', 'Merging', 'Reinforcement Learning', 'Pretraining Methods']
---
Recent advancements in text-to-video (T2V) generation have been driven by two
competing paradigms: autoregressive language models and diffusion models.
However, each paradigm has intrinsic limitations: language models struggle with
visual quality and error accumulation, while diffusion models lack semantic
understanding and causal modeling. In this work, we propose LanDiff, a hybrid
framework that synergizes the strengths of both paradigms through
coarse-to-fine generation. Our architecture introduces three key innovations:
(1) a semantic tokenizer that compresses 3D visual features into compact 1D
discrete representations through efficient semantic compression, achieving a
\\(\sim\\)14,000\\(\times\\) compression ratio; (2) a language model that generates
semantic tokens with high-level semantic relationships; (3) a streaming
diffusion model that refines coarse semantics into high-fidelity videos.
Experiments show that LanDiff, a 5B model, achieves a score of 85.43 on the
VBench T2V benchmark, surpassing the state-of-the-art open-source models
Hunyuan Video (13B) and other commercial models such as Sora, Kling, and
Hailuo. Furthermore, our model also achieves state-of-the-art performance in
long video generation, surpassing other open-source models in this field. Our
demo can be viewed at https://landiff.github.io/.
