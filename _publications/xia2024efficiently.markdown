---
layout: publication
title: FP645;LLM Efficiently Serving Large Language Models Through Fp645;centric Algorithm45;system Co45;design
authors: Xia Haojun, Zheng Zhen, Wu Xiaoxia, Chen Shiyang, Yao Zhewei, Youn Stephen, Bakhtiari Arash, Wyatt Michael, Zhuang Donglin, Zhou Zhongzhu, Ruwase Olatunji, He Yuxiong, Song Shuaiwen Leon
conference: "Arxiv"
year: 2024
bibkey: xia2024efficiently
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.14112"}
  - {name: "Code", url: "https://github.com/usyd&#45;fsalab/fp6&#95;llm"}
tags: ['Applications', 'Efficiency And Optimization', 'Has Code', 'Quantization', 'Reinforcement Learning']
---
Six45;bit quantization (FP6) can effectively reduce the size of large language models (LLMs) and preserve the model quality consistently across varied applications. However existing systems do not provide Tensor Core support for FP6 quantization and struggle to achieve practical performance improvements during LLM inference. It is challenging to support FP6 quantization on GPUs due to (1) unfriendly memory access of model weights with irregular bit45;width and (2) high runtime overhead of weight de45;quantization. To address these problems we propose TC45;FPx the first full45;stack GPU kernel design scheme with unified Tensor Core support of float45;point weights for various quantization bit45;width. We integrate TC45;FPx kernel into an existing inference system providing new end45;to45;end support (called FP645;LLM) for quantized LLM inference where better trade45;offs between inference cost and model quality are achieved. Experiments show that FP645;LLM enables the inference of LLaMA45;70b using only a single GPU achieving 1.69x45;2.65x higher normalized inference throughput than the FP16 baseline. The source code is publicly available at https://github.com/usyd&#45;fsalab/fp6&#95;llm.
