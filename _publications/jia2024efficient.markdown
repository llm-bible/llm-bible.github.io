---
layout: publication
title: 'Efficient Streaming LLM For Speech Recognition'
authors: Junteng Jia, Gil Keren, Wei Zhou, Egor Lakomkin, Xiaohui Zhang, Chunyang Wu, Frank Seide, Jay Mahadeokar, Ozlem Kalinli
conference: "Arxiv"
year: 2024
bibkey: jia2024efficient
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.03752'}
tags: ['Attention Mechanism', 'INTERSPEECH', 'Training Techniques', 'Model Architecture', 'Prompting', 'Reinforcement Learning']
---
Recent works have shown that prompting large language models with audio
encodings can unlock speech recognition capabilities. However, existing
techniques do not scale efficiently, especially while handling long form
streaming audio inputs -- not only do they extrapolate poorly beyond the audio
length seen during training, but they are also computationally inefficient due
to the quadratic cost of attention.
  In this work, we introduce SpeechLLM-XL, a linear scaling decoder-only model
for streaming speech recognition. We process audios in configurable chunks
using limited attention window for reduced computation, and the text tokens for
each audio chunk are generated auto-regressively until an EOS is predicted.
During training, the transcript is segmented into chunks, using a CTC forced
alignment estimated from encoder output. SpeechLLM-XL with 1.28 seconds chunk
size achieves 2.7%/6.7% WER on LibriSpeech test clean/other, and it shows no
quality degradation on long form utterances 10x longer than the training
utterances.
