---
layout: publication
title: 'Sketch To Adapt: Fine-tunable Sketches For Efficient LLM Adaptation'
authors: Tianyi Zhang, Junda Su, Aditya Desai, Oscar Wu, Zhaozhuo Xu, Anshumali Shrivastava
conference: "Arxiv"
year: 2024
bibkey: zhang2024sketch
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.06364"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'Quantization', 'Pretraining Methods', 'Fine-Tuning']
---
Adapting pre-trained large language models (LLMs) is crucial but challenging
due to their enormous size. Parameter-efficient fine-tuning (PEFT) techniques
typically employ additive adapters applied to frozen model weights. To further
reduce memory usage, model weights can be compressed through quantization.
However, existing PEFT methods often yield suboptimal model quality due to
restrictive assumptions, such as imposing low-rank constraints on adapters to
reduce trainable parameters. We find that sketching, a popular data compression
technique, can serve as an efficient adaptation strategy for LLMs while
avoiding low-rank assumptions. We introduce SketchTune, a compressive
adaptation strategy that compresses LLM weights into compact fine-tunable
sketches, integrating compression and adaptation into a unified framework. This
integration eliminates the need for complex two-path computation common in
existing PEFT techniques, enabling faster and more memory-efficient training
and inference. SketchTune is supported by mathematical insights into matrix
classes that are better approximated using sketching rather than low-rank
methods. Our rigorous evaluations with Llama-1/2/3 models demonstrate that
SketchTune outperforms leading PEFT methods across diverse tasks including math
problem-solving, common sense reasoning, and instruction following, while using
substantially smaller base models and comparable trainable parameters. As a
highlight, SketchTune outperforms LoRA, DoRA, and S2FT on commonsense and math
benchmarks using 2.6-3.5\\(\times\\) smaller base models and exceeds LoftQ in
accuracy by 14.48% on GSM8K with 7.3\\(\times\\) fewer trainable parameters.
