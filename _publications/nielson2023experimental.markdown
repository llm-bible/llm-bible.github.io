---
layout: publication
title: An Experimental Study Assessing The Combined Framework Of Wavlm And BEST45;RQ For Text45;to45;speech Synthesis
authors: Nielson Via, Hillis Steven
conference: "Arxiv"
year: 2023
bibkey: nielson2023experimental
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.05415"}
tags: ['Efficiency And Optimization', 'Model Architecture', 'Quantization', 'Reinforcement Learning', 'Tools']
---
We propose a new model architecture specifically suited for text45;to45;speech (TTS) models. We combine WavLM a pre45;trained self45;supervised learning (SSL) speech model and the BEST45;RQ vector quantization framework. We assess the extent to which the more task45;agnostic WavLM coupled with the superior suitability of the simplistic BEST45;RQ framework for a wider array of downstream tasks yields favorable outcomes. Experiments on the LibriSpeech dataset with SUPERB benchmarking assert that the proposed model significantly underperforms. We speculate the underlying reason for this performance is related to the difference between featurizing raw audio waveforms and spectrograms with a quantizer. We discuss the limitations of this approach to better guide future advancements in TTS.
