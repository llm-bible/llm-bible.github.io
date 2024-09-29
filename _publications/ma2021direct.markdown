---
layout: publication
title: 'Direct Simultaneous Speech-to-speech Translation With Variational Monotonic Multihead Attention'
authors: Ma Xutai, Gong Hongyu, Liu Danni, Lee Ann, Tang Yun, Chen Peng-jen, Hsu Wei-ning, Koehn Phillip, Pino Juan
conference: "Arxiv"
year: 2021
bibkey: ma2021direct
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2110.08250"}
tags: ['Attention Mechanism', 'Model Architecture', 'RAG']
---
We present a direct simultaneous speech-to-speech translation (Simul-S2ST) model Furthermore the generation of translation is independent from intermediate text representations. Our approach leverages recent progress on direct speech-to-speech translation with discrete units in which a sequence of discrete representations instead of continuous spectrogram features learned in an unsupervised manner are predicted from the model and passed directly to a vocoder for speech synthesis on-the-fly. We also introduce the variational monotonic multihead attention (V-MMA) to handle the challenge of inefficient policy learning in speech simultaneous translation. The simultaneous policy then operates on source speech features and target discrete units. We carry out empirical studies to compare cascaded and direct approach on the Fisher Spanish-English and MuST-C English-Spanish datasets. Direct simultaneous model is shown to outperform the cascaded model by achieving a better tradeoff between translation quality and latency.
