---
layout: publication
title: 'Can Large Language Models Understand Context?'
authors: Yilun Zhu, Joel Ruben Antony Moniz, Shruti Bhargava, Jiarui Lu, Dhivya Piraviperumal, Site Li, Yuan Zhang, Hong Yu, Bo-hsiang Tseng
conference: "Arxiv"
year: 2024
bibkey: zhu2024can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.00858"}
tags: ['Efficiency and Optimization', 'Applications', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods', 'Quantization', 'Prompting', 'In-Context Learning']
---
Understanding context is key to understanding human language, an ability
which Large Language Models (LLMs) have been increasingly seen to demonstrate
to an impressive extent. However, though the evaluation of LLMs encompasses
various domains within the realm of Natural Language Processing, limited
attention has been paid to probing their linguistic capability of understanding
contextual features. This paper introduces a context understanding benchmark by
adapting existing datasets to suit the evaluation of generative models. This
benchmark comprises of four distinct tasks and nine datasets, all featuring
prompts designed to assess the models' ability to understand context. First, we
evaluate the performance of LLMs under the in-context learning pretraining
scenario. Experimental results indicate that pre-trained dense models struggle
with understanding more nuanced contextual features when compared to
state-of-the-art fine-tuned models. Second, as LLM compression holds growing
significance in both research and real-world applications, we assess the
context understanding of quantized models under in-context-learning settings.
We find that 3-bit post-training quantization leads to varying degrees of
performance reduction on our benchmark. We conduct an extensive analysis of
these scenarios to substantiate our experimental results.
