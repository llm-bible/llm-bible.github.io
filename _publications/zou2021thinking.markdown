---
layout: publication
title: 'Thinking Clearly, Talking Fast: Concept-guided Non-autoregressive Generation For Open-domain Dialogue Systems'
authors: Yicheng Zou, Zhihua Liu, Xingwu Hu, Qi Zhang
conference: "Arxiv"
year: 2021
citations: 25
bibkey: zou2021thinking
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2109.04084'}
tags: ['Language Modeling', 'Transformer', 'GPT', 'Model Architecture', 'Tools', 'Applications', 'Reinforcement Learning', 'Pretraining Methods']
---
Human dialogue contains evolving concepts, and speakers naturally associate
multiple concepts to compose a response. However, current dialogue models with
the seq2seq framework lack the ability to effectively manage concept
transitions and can hardly introduce multiple concepts to responses in a
sequential decoding manner. To facilitate a controllable and coherent dialogue,
in this work, we devise a concept-guided non-autoregressive model (CG-nAR) for
open-domain dialogue generation. The proposed model comprises a multi-concept
planning module that learns to identify multiple associated concepts from a
concept graph and a customized Insertion Transformer that performs
concept-guided non-autoregressive generation to complete a response. The
experimental results on two public datasets show that CG-nAR can produce
diverse and coherent responses, outperforming state-of-the-art baselines in
both automatic and human evaluations with substantially faster inference speed.
