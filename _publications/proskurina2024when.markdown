---
layout: publication
title: 'When Quantization Affects Confidence Of Large Language Models?'
authors: Irina Proskurina, Luc Brun, Guillaume Metzler, Julien Velcin
conference: "Arxiv"
year: 2024
bibkey: proskurina2024when
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2405.00632'}
tags: ['Interpretability and Explainability', 'RAG', 'Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'GPT', 'Quantization', 'Ethics and Bias']
---
Recent studies introduced effective compression techniques for Large Language
Models (LLMs) via post-training quantization or low-bit weight representation.
Although quantized weights offer storage efficiency and allow for faster
inference, existing works have indicated that quantization might compromise
performance and exacerbate biases in LLMs. This study investigates the
confidence and calibration of quantized models, considering factors such as
language model type and scale as contributors to quantization loss. Firstly, we
reveal that quantization with GPTQ to 4-bit results in a decrease in confidence
regarding true labels, with varying impacts observed among different language
models. Secondly, we observe fluctuations in the impact on confidence across
different scales. Finally, we propose an explanation for quantization loss
based on confidence levels, indicating that quantization disproportionately
affects samples where the full model exhibited low confidence levels in the
first place.
