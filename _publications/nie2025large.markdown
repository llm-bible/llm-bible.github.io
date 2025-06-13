---
layout: publication
title: 'Large Language Diffusion Models'
authors: Shen Nie, Fengqi Zhu, Zebin You, Xiaolu Zhang, Jingyang Ou, Jun Hu, Jun Zhou, Yankai Lin, Ji-rong Wen, Chongxuan Li
conference: "Arxiv"
year: 2025
bibkey: nie2025large
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.09992'}
  - {name: "Code", url: 'https://ml-gsai.github.io/LLaDA-demo/'}
tags: ['Has Code', 'Language Modeling', 'Transformer', 'Training Techniques', 'Model Architecture', 'GPT', 'Fine-Tuning', 'Merging', 'Prompting', 'Pre-Training', 'In-Context Learning', 'Pretraining Methods']
---
Autoregressive models (ARMs) are widely regarded as the cornerstone of large
language models (LLMs). We challenge this notion by introducing LLaDA, a
diffusion model trained from scratch under the pre-training and supervised
fine-tuning (SFT) paradigm. LLaDA models distributions through a forward data
masking process and a reverse process, parameterized by a vanilla Transformer
to predict masked tokens. By optimizing a likelihood bound, it provides a
principled generative approach for probabilistic inference. Across extensive
benchmarks, LLaDA demonstrates strong scalability, outperforming our
self-constructed ARM baselines. Remarkably, LLaDA 8B is competitive with strong
LLMs like LLaMA3 8B in in-context learning and, after SFT, exhibits impressive
instruction-following abilities in case studies such as multi-turn dialogue.
Moreover, LLaDA addresses the reversal curse, surpassing GPT-4o in a reversal
poem completion task. Our findings establish diffusion models as a viable and
promising alternative to ARMs, challenging the assumption that key LLM
capabilities discussed above are inherently tied to ARMs. Project page and
codes: https://ml-gsai.github.io/LLaDA-demo/.
