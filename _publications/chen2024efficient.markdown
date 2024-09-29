---
layout: publication
title: Efficientqat\: Efficient Quantization-aware Training For Large Language Models
authors: Chen Mengzhao, Shao Wenqi, Xu Peng, Wang Jiahao, Gao Peng, Zhang Kaipeng, Qiao Yu, Luo Ping
conference: "Arxiv"
year: 2024
bibkey: chen2024efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.11062"}
  - {name: "Code", url: "https://github.com/OpenGVLab/EfficientQAT"}
tags: ['Efficiency And Optimization', 'Has Code', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Quantization', 'Training Techniques', 'Transformer']
---
Large language models (LLMs) are integral to modern natural language processing and artificial intelligence. However they face challenges in managing their significant memory requirements. Although quantization-aware training (QAT) offers a solution by reducing memory consumption through low-bit representations with minimal accuracy loss it demands substantial training resources to optimize model weights and quantization parameters. To address this we propose Efficient Quantization-Aware Training (EfficientQAT) a novel quantization technique for compressing LLMs. EfficientQAT involves two consecutive phases Block-wise training of all parameters (Block-AP) and end-to-end training of quantization parameters (E2E-QP). Block-AP sequentially conducts quantization-aware training for all parameters in each transformer block with block-wise reconstruction maintaining efficiency by avoiding training the entire LLM. Initialized with quantized model E2E-QP then trains only quantization parameters (step sizes) end-to-end enhancing efficiency with a fixed quantized backbone and reduced trainable parameter count. Extensive experiments demonstrate that EfficientQAT outperforms previous quantization methods across a range of models including base LLMs instruction-tuned LLMs and multimodal LLMs with scales from 7B to 70B parameters at various quantization bits. For instance EfficientQAT obtains a 2-bit Llama-2-70B model on a single A100-80GB GPU in 41 hours with less than 337; accuracy degradation compared to the full precision (69.48 vs. 72.41). Notably this INT2 quantized 70B model obtains a 1.67 accuracy gain over the Llama-2-13B model (69.48 vs. 67.81) while requiring less memory (19.2GB vs. 24.2GB). Code is available at https://github.com/OpenGVLab/EfficientQAT."
