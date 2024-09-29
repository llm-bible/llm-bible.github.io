---
layout: publication
title: Learning Ui45;to45;code Reverse Generator Using Visual Critic Without Rendering
authors: Soselia Davit, Saifullah Khalid, Zhou Tianyi
conference: "Arxiv"
year: 2023
bibkey: soselia2023learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.14637"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Transformer']
---
Automated reverse engineering of HTML/CSS code from UI screenshots is an important yet challenging problem with broad applications in website development and design. In this paper we propose a novel vision45;code transformer (ViCT) composed of a vision encoder processing the screenshots and a language decoder to generate the code. They are initialized by pre45;trained models such as ViT/DiT and GPT45;2/LLaMA but aligning the two modalities requires end45;to45;end finetuning which aims to minimize the visual discrepancy between the code45;rendered webpage and the original screenshot. However the rendering is non45;differentiable and causes costly overhead. We address this problem by actor45;critic fine45;tuning where a visual critic without rendering (ViCR) is developed to predict visual discrepancy given the original and generated code. To train and evaluate our models we created two synthetic datasets of varying complexity with over 75000 unique (code screenshot) pairs. We evaluate the UI45;to45;Code performance using a combination of automated metrics such as MSE BLEU IoU and a novel htmlBLEU score. ViCT outperforms a strong baseline model DiT45;GPT2 improving IoU from 0.64 to 0.79 and lowering MSE from 12.25 to 9.02. With much lower computational cost it can achieve comparable performance as when using a larger decoder such as LLaMA.
