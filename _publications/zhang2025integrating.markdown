---
layout: publication
title: 'Inspiremusic: Integrating Super Resolution And Large Language Model For High-fidelity Long-form Music Generation'
authors: Chong Zhang, Yukun Ma, Qian Chen, Wen Wang, Shengkui Zhao, Zexu Pan, Hao Wang, Chongjia Ni, Trung Hieu Nguyen, Kun Zhou, Yidi Jiang, Chaohong Tan, Zhifu Gao, Zhihao Du, Bin Ma
conference: "Arxiv"
year: 2025
bibkey: zhang2025integrating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.00084'}
  - {name: "Code", url: 'https://github.com/FunAudioLLM/InspireMusic'}
tags: ['Has Code', 'Transformer', 'Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Tools', 'GPT', 'Prompting', 'Pretraining Methods']
---
We introduce InspireMusic, a framework integrated super resolution and large
language model for high-fidelity long-form music generation. A unified
framework generates high-fidelity music, songs, and audio, which incorporates
an autoregressive transformer with a super-resolution flow-matching model. This
framework enables the controllable generation of high-fidelity long-form music
at a higher sampling rate from both text and audio prompts. Our model differs
from previous approaches, as we utilize an audio tokenizer with one codebook
that contains richer semantic information, thereby reducing training costs and
enhancing efficiency. This combination enables us to achieve high-quality audio
generation with long-form coherence of up to \\(8\\) minutes. Then, an
autoregressive transformer model based on Qwen 2.5 predicts audio tokens. Next,
we employ a super-resolution flow-matching model to generate high-sampling rate
audio with fine-grained details learned from an acoustic codec model.
Comprehensive experiments show that the InspireMusic-1.5B-Long model has a
comparable performance to recent top-tier open-source systems, including
MusicGen and Stable Audio 2.0, on subjective and objective evaluations. The
code and pre-trained models are released at
https://github.com/FunAudioLLM/InspireMusic.
