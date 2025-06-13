---
layout: publication
title: 'Prompting And Adapter Tuning For Self-supervised Encoder-decoder Speech Model'
authors: Kai-wei Chang, Ming-hsin Chen, Yun-ping Lin, Jing Neng Hsu, Paul Kuo-ming Huang, Chien-yu Huang, Shang-wen Li, Hung-yi Lee
conference: "Arxiv"
year: 2023
bibkey: chang2023prompting
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2310.02971'}
tags: ['Fine-Tuning', 'Prompting', 'Training Techniques', 'Pretraining Methods']
---
Prompting and adapter tuning have emerged as efficient alternatives to
fine-tuning (FT) methods. However, existing studies on speech prompting focused
on classification tasks and failed on more complex sequence generation tasks.
Besides, adapter tuning is primarily applied with a focus on encoder-only
self-supervised models. Our experiments show that prompting on Wav2Seq, a
self-supervised encoder-decoder model, surpasses previous works in sequence
generation tasks. It achieves a remarkable 53% relative improvement in word
error rate for ASR and a 27% in F1 score for slot filling. Additionally,
prompting competes with the FT method in the low-resource scenario. Moreover,
we show the transferability of prompting and adapter tuning on Wav2Seq in
cross-lingual ASR. When limited trainable parameters are involved, prompting
and adapter tuning consistently outperform conventional FT across 7 languages.
Notably, in the low-resource scenario, prompting consistently outperforms
adapter tuning.
