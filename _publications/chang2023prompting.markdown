---
layout: publication
title: 'Prompting And Adapter Tuning For Self-supervised Encoder-decoder Speech Model'
authors: Chang Kai-wei, Chen Ming-hsin, Lin Yun-ping, Hsu Jing Neng, Huang Paul Kuo-ming, Huang Chien-yu, Li Shang-wen, Lee Hung-yi
conference: "Arxiv"
year: 2023
bibkey: chang2023prompting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.02971"}
tags: ['Fine Tuning', 'Pretraining Methods', 'Prompting', 'Training Techniques']
---
'Prompting and adapter tuning have emerged as efficient alternatives to fine-tuning (FT) methods. However, existing studies on speech prompting focused on classification tasks and failed on more complex sequence generation tasks. Besides, adapter tuning is primarily applied with a focus on encoder-only self-supervised models. Our experiments show that prompting on Wav2Seq, a self-supervised encoder-decoder model, surpasses previous works in sequence generation tasks. It achieves a remarkable 53&#37; relative improvement in word error rate for ASR and a 27&#37; in F1 score for slot filling. Additionally, prompting competes with the FT method in the low-resource scenario. Moreover, we show the transferability of prompting and adapter tuning on Wav2Seq in cross-lingual ASR. When limited trainable parameters are involved, prompting and adapter tuning consistently outperform conventional FT across 7 languages. Notably, in the low-resource scenario, prompting consistently outperforms adapter tuning.'
