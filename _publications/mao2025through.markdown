---
layout: publication
title: 'Through The Magnifying Glass: Adaptive Perception Magnification For Hallucination-free VLM Decoding'
authors: Shunqi Mao, Chaoyi Zhang, Weidong Cai
conference: "Arxiv"
year: 2025
bibkey: mao2025through
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.10183"}
  - {name: "Code", url: "https://github.com/ShunqiM/PM"}
tags: ['Ethics and Bias', 'Model Architecture', 'Attention Mechanism', 'Has Code', 'Multimodal Models']
---
Existing vision-language models (VLMs) often suffer from visual
hallucination, where the generated responses contain inaccuracies that are not
grounded in the visual input. Efforts to address this issue without model
finetuning primarily mitigate hallucination by reducing biases contrastively or
amplifying the weights of visual embedding during decoding. However, these
approaches improve visual perception at the cost of impairing the language
reasoning capability. In this work, we propose the Perception Magnifier (PM), a
novel visual decoding method that iteratively isolates relevant visual tokens
based on attention and magnifies the corresponding regions, spurring the model
to concentrate on fine-grained visual details during decoding. Specifically, by
magnifying critical regions while preserving the structural and contextual
information at each decoding step, PM allows the VLM to enhance its scrutiny of
the visual input, hence producing more accurate and faithful responses.
Extensive experimental results demonstrate that PM not only achieves superior
hallucination mitigation but also enhances language generation while preserving
strong reasoning capabilities. Code is available at
https://github.com/ShunqiM/PM .
