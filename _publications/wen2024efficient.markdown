---
layout: publication
title: 'Efficient Vision-language Models By Summarizing Visual Tokens Into Compact Registers'
authors: Yuxin Wen, Qingqing Cao, Qichen Fu, Sachin Mehta, Mahyar Najibi
conference: "Arxiv"
year: 2024
bibkey: wen2024efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.14072"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Multimodal Models', 'Model Architecture', 'Reinforcement Learning', 'GPT', 'Pretraining Methods', 'Transformer', 'Prompting', 'Applications']
---
Recent advancements in vision-language models (VLMs) have expanded their
potential for real-world applications, enabling these models to perform complex
reasoning on images. In the widely used fully autoregressive transformer-based
models like LLaVA, projected visual tokens are prepended to textual tokens.
Oftentimes, visual tokens are significantly more than prompt tokens, resulting
in increased computational overhead during both training and inference. In this
paper, we propose Visual Compact Token Registers (Victor), a method that
reduces the number of visual tokens by summarizing them into a smaller set of
register tokens. Victor adds a few learnable register tokens after the visual
tokens and summarizes the visual information into these registers using the
first few layers in the language tower of VLMs. After these few layers, all
visual tokens are discarded, significantly improving computational efficiency
for both training and inference. Notably, our method is easy to implement and
requires a small number of new trainable parameters with minimal impact on
model performance. In our experiment, with merely 8 visual registers--about 1%
of the original tokens--Victor shows less than a 4% accuracy drop while
reducing the total training time by 43% and boosting the inference throughput
by 3.3X.
