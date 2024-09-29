---
layout: publication
title: FP6-LLM Efficiently Serving Large Language Models Through Fp6-centric Algorithm-system Co-design
authors: Xia Haojun, Zheng Zhen, Wu Xiaoxia, Chen Shiyang, Yao Zhewei, Youn Stephen, Bakhtiari Arash, Wyatt Michael, Zhuang Donglin, Zhou Zhongzhu, Ruwase Olatunji, He Yuxiong, Song Shuaiwen Leon
conference: "Arxiv"
year: 2024
bibkey: xia2024efficiently
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.14112"}
  - {name: "Code", url: "https://github.com/usyd-fsalab/fp6_llm"}
tags: ['Applications', 'Efficiency And Optimization', 'Has Code', 'Quantization', 'Reinforcement Learning']
---
Six-bit quantization (FP6) can effectively reduce the size of large language models (LLMs) and preserve the model quality consistently across varied applications. However existing systems do not provide Tensor Core support for FP6 quantization and struggle to achieve practical performance improvements during LLM inference. It is challenging to support FP6 quantization on GPUs due to (1) unfriendly memory access of model weights with irregular bit-width and (2) high runtime overhead of weight de-quantization. To address these problems we propose TC-FPx the first full-stack GPU kernel design scheme with unified Tensor Core support of float-point weights for various quantization bit-width. We integrate TC-FPx kernel into an existing inference system providing new end-to-end support (called FP6-LLM) for quantized LLM inference where better trade-offs between inference cost and model quality are achieved. Experiments show that FP6-LLM enables the inference of LLaMA-70b using only a single GPU achieving 1.69x-2.65x higher normalized inference throughput than the FP16 baseline. The source code is publicly available at https://github.com/usyd-fsalab/fp6\_llm.
