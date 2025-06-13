---
layout: publication
title: 'Low-bit Quantization Favors Undertrained Llms: Scaling Laws For Quantized Llms With 100T Training Tokens'
authors: Xu Ouyang, Tao Ge, Thomas Hartvigsen, Zhisong Zhang, Haitao Mi, Dong Yu
conference: "Arxiv"
year: 2024
bibkey: ouyang2024low
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.17691"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Scaling Laws', 'Quantization', 'Large-Scale Training', 'Pre-Training']
---
We reveal that low-bit quantization favors undertrained large language models
(LLMs) by observing that models with larger sizes or fewer training tokens
experience less quantization-induced degradation (QiD) when applying low-bit
quantization, whereas smaller models with extensive training tokens suffer
significant QiD. To gain deeper insights into this trend, we study over 1500
quantized LLM checkpoints of various sizes and at different training levels
(undertrained or fully trained) in a controlled setting, deriving scaling laws
for understanding the relationship between QiD and factors such as the number
of training tokens, model size and bit width.
  With the derived scaling laws, we propose a novel perspective that we can use
QiD to measure an LLM's training levels and determine the number of training
tokens required for fully training LLMs of various sizes. Moreover, we use the
scaling laws to predict the quantization performance of different-sized LLMs
trained with 100 trillion tokens. Our projection shows that the low-bit
quantization performance of future models, which are expected to be trained
with over 100 trillion tokens, may NOT be desirable. This poses a potential
challenge for low-bit quantization in the future and highlights the need for
awareness of a model's training level when evaluating low-bit quantization
research. To facilitate future research on this problem, we release all the
1500+ quantized checkpoints used in this work at
https://huggingface.co/Xu-Ouyang.
