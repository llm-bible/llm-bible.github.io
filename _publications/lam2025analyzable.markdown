---
layout: publication
title: 'Analyzable Chain-of-musical-thought Prompting For High-fidelity Music Generation'
authors: Max W. Y. Lam, Yijin Xing, Weiya You, Jingcheng Wu, Zongyu Yin, Fuqiang Jiang, Hangyu Liu, Feng Liu, Xingda Li, Wei-tsung Lu, Hanyu Chen, Tong Feng, Tianwei Zhao, Chien-hung Liu, Xuchen Song, Yang Li, Yahui Zhou
conference: "Arxiv"
year: 2025
bibkey: lam2025analyzable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.19611"}
tags: ['GPT', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods', 'Prompting']
---
Autoregressive (AR) models have demonstrated impressive capabilities in
generating high-fidelity music. However, the conventional next-token prediction
paradigm in AR models does not align with the human creative process in music
composition, potentially compromising the musicality of generated samples. To
overcome this limitation, we introduce MusiCoT, a novel chain-of-thought (CoT)
prompting technique tailored for music generation. MusiCoT empowers the AR
model to first outline an overall music structure before generating audio
tokens, thereby enhancing the coherence and creativity of the resulting
compositions. By leveraging the contrastive language-audio pretraining (CLAP)
model, we establish a chain of "musical thoughts", making MusiCoT scalable and
independent of human-labeled data, in contrast to conventional CoT methods.
Moreover, MusiCoT allows for in-depth analysis of music structure, such as
instrumental arrangements, and supports music referencing -- accepting
variable-length audio inputs as optional style references. This innovative
approach effectively addresses copying issues, positioning MusiCoT as a vital
practical method for music prompting. Our experimental results indicate that
MusiCoT consistently achieves superior performance across both objective and
subjective metrics, producing music quality that rivals state-of-the-art
generation models.
  Our samples are available at https://MusiCoT.github.io/.
