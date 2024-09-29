---
layout: publication
title: Prompting And Adapter Tuning For Self45;supervised Encoder45;decoder Speech Model
authors: Chang Kai-wei, Chen Ming-hsin, Lin Yun-ping, Hsu Jing Neng, Huang Paul Kuo-ming, Huang Chien-yu, Li Shang-wen, Lee Hung-yi
conference: "Arxiv"
year: 2023
bibkey: chang2023prompting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.02971"}
tags: ['Applications', 'Prompting']
---
Prompting and adapter tuning have emerged as efficient alternatives to fine45;tuning (FT) methods. However existing studies on speech prompting focused on classification tasks and failed on more complex sequence generation tasks. Besides adapter tuning is primarily applied with a focus on encoder45;only self45;supervised models. Our experiments show that prompting on Wav2Seq a self45;supervised encoder45;decoder model surpasses previous works in sequence generation tasks. It achieves a remarkable 5337; relative improvement in word error rate for ASR and a 2737; in F1 score for slot filling. Additionally prompting competes with the FT method in the low45;resource scenario. Moreover we show the transferability of prompting and adapter tuning on Wav2Seq in cross45;lingual ASR. When limited trainable parameters are involved prompting and adapter tuning consistently outperform conventional FT across 7 languages. Notably in the low45;resource scenario prompting consistently outperforms adapter tuning.
