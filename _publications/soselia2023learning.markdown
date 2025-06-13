---
layout: publication
title: 'Learning Ui-to-code Reverse Generator Using Visual Critic Without Rendering'
authors: Davit Soselia, Khalid Saifullah, Tianyi Zhou
conference: "Arxiv"
year: 2023
bibkey: soselia2023learning
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2305.14637'}
tags: ['Transformer', 'Training Techniques', 'Applications', 'Model Architecture', 'Fine-Tuning', 'GPT', 'Reinforcement Learning', 'Pretraining Methods']
---
Automated reverse engineering of HTML/CSS code from UI screenshots is an
important yet challenging problem with broad applications in website
development and design. In this paper, we propose a novel vision-code
transformer (ViCT) composed of a vision encoder processing the screenshots and
a language decoder to generate the code. They are initialized by pre-trained
models such as ViT/DiT and GPT-2/LLaMA but aligning the two modalities requires
end-to-end finetuning, which aims to minimize the visual discrepancy between
the code-rendered webpage and the original screenshot. However, the rendering
is non-differentiable and causes costly overhead. We address this problem by
actor-critic fine-tuning where a visual critic without rendering (ViCR) is
developed to predict visual discrepancy given the original and generated code.
To train and evaluate our models, we created two synthetic datasets of varying
complexity, with over 75,000 unique (code, screenshot) pairs. We evaluate the
UI-to-Code performance using a combination of automated metrics such as MSE,
BLEU, IoU, and a novel htmlBLEU score. ViCT outperforms a strong baseline model
DiT-GPT2, improving IoU from 0.64 to 0.79 and lowering MSE from 12.25 to 9.02.
With much lower computational cost, it can achieve comparable performance as
when using a larger decoder such as LLaMA.
