---
layout: publication
title: Generative Pretrained Structured Transformers&#58; Unsupervised Syntactic Language Models At Scale
authors: Hu Xiang, Ji Pengyu, Zhu Qingyang, Wu Wei, Tu Kewei
conference: "Arxiv"
year: 2024
bibkey: hu2024generative
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.08293"}
tags: ['GPT', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
A syntactic language model (SLM) incrementally generates a sentence with its syntactic tree in a left-to-right manner. We present Generative Pretrained Structured Transformers (GPST) an unsupervised SLM at scale capable of being pre-trained from scratch on raw texts with high parallelism. GPST circumvents the limitations of previous SLMs such as relying on gold trees and sequential training. It consists of two components a usual SLM supervised by a uni-directional language modeling loss and an additional composition model which induces syntactic parse trees and computes constituent representations supervised by a bi-directional language modeling loss. We propose a representation surrogate to enable joint parallel training of the two models in a hard-EM fashion. We pre-train GPST on OpenWebText a corpus with 9 billion tokens and demonstrate the superiority of GPST over GPT-2 with a comparable size in numerous tasks covering both language understanding and language generation. Meanwhile GPST also significantly outperforms existing unsupervised SLMs on left-to-right grammar induction while holding a substantial acceleration on training.
