---
layout: publication
title: PB45;LLM Partially Binarized Large Language Models
authors: Shang Yuzhang, Yuan Zhihang, Wu Qiang, Dong Zhen
conference: "Arxiv"
year: 2023
bibkey: shang2023pb
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.00034"}
  - {name: "Code", url: "https://github.com/hahnyuan/BinaryLLM"}
tags: ['Applications', 'Efficiency And Optimization', 'Fine Tuning', 'GPT', 'Has Code', 'Model Architecture', 'Quantization', 'RAG', 'Training Techniques']
---
This paper explores network binarization a radical form of quantization compressing model weights to a single bit specifically for Large Language Models (LLMs) compression. Due to previous binarization methods collapsing LLMs we propose a novel approach Partially45;Binarized LLM (PB45;LLM) which can achieve extreme low45;bit quantization while maintaining the linguistic reasoning capacity of quantized LLMs. Specifically our exploration first uncovers the ineffectiveness of naive applications of existing binarization algorithms and highlights the imperative role of salient weights in achieving low45;bit quantization. Thus PB45;LLM filters a small ratio of salient weights during binarization allocating them to higher45;bit storage i.e. partially45;binarization. PB45;LLM is extended to recover the capacities of quantized LMMs by analyzing from the perspective of post45;training quantization (PTQ) and quantization45;aware training (QAT). Under PTQ combining the concepts from GPTQ we reconstruct the binarized weight matrix guided by the Hessian matrix and successfully recover the reasoning capacity of PB45;LLM in low45;bit. Under QAT we freeze the salient weights during training explore the derivation of optimal scaling factors crucial for minimizing the quantization error and propose a scaling mechanism based on this derived scaling strategy for residual binarized weights. Those explorations and the developed methodologies significantly contribute to rejuvenating the performance of low45;bit quantized LLMs and present substantial advancements in the field of network binarization for LLMs.The code is available at https://github.com/hahnyuan/BinaryLLM.
