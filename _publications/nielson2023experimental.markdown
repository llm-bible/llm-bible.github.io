---
layout: publication
title: 'An Experimental Study: Assessing The Combined Framework Of Wavlm And BEST-RQ For Text-to-speech Synthesis'
authors: Nielson Via, Hillis Steven
conference: "Arxiv"
year: 2023
bibkey: nielson2023experimental
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.05415"}
tags: ['Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Quantization', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
We propose a new model architecture specifically suited for text-to-speech (TTS) models. We combine WavLM a pre-trained self-supervised learning (SSL) speech model and the BEST-RQ vector quantization framework. We assess the extent to which the more task-agnostic WavLM coupled with the superior suitability of the simplistic BEST-RQ framework for a wider array of downstream tasks yields favorable outcomes. Experiments on the LibriSpeech dataset with SUPERB benchmarking assert that the proposed model significantly underperforms. We speculate the underlying reason for this performance is related to the difference between featurizing raw audio waveforms and spectrograms with a quantizer. We discuss the limitations of this approach to better guide future advancements in TTS.
