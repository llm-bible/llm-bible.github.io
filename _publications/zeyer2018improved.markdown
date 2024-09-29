---
layout: publication
title: "Improved Training Of End-to-end Attention Models For Speech Recognition"
authors: Zeyer Albert, Irie Kazuki, Schlüter Ralf, Ney Hermann
conference: "Arxiv"
year: 2018
bibkey: zeyer2018improved
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1805.03294"}
tags: ['Attention Mechanism', 'Merging', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
Sequence-to-sequence attention-based models on subword units allow simple open-vocabulary end-to-end speech recognition. In this work we show that such models can achieve competitive results on the Switchboard 300h and LibriSpeech 1000h tasks. In particular we report the state-of-the-art word error rates (WER) of 3.5437; on the dev-clean and 3.8237; on the test-clean evaluation subsets of LibriSpeech. We introduce a new pretraining scheme by starting with a high time reduction factor and lowering it during training which is crucial both for convergence and final performance. In some experiments we also use an auxiliary CTC loss function to help the convergence. In addition we train long short-term memory (LSTM) language models on subword units. By shallow fusion we report up to 2737; relative improvements in WER over the attention baseline without a language model.
