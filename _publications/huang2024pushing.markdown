---
layout: publication
title: Billm Pushing The Limit Of Post45;training Quantization For Llms
authors: Huang Wei, Liu Yangdong, Qin Haotong, Li Ying, Zhang Shiming, Liu Xianglong, Magno Michele, Qi Xiaojuan
conference: "Arxiv"
year: 2024
bibkey: huang2024pushing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.04291"}
  - {name: "Code", url: "https://github.com/Aaronhuang&#45;778/BiLLM"}
tags: ['Efficiency And Optimization', 'Has Code', 'Quantization', 'Training Techniques']
---
Pretrained large language models (LLMs) exhibit exceptional general language processing capabilities but come with significant demands on memory and computational resources. As a powerful compression technology binarization can extremely reduce model weights to a mere 1 bit lowering the expensive computation and memory requirements. However existing quantization techniques fall short of maintaining LLM performance under ultra45;low bit45;widths. In response to this challenge we present BiLLM a groundbreaking 145;bit post45;training quantization scheme tailored for pretrained LLMs. Based on the weight distribution of LLMs BiLLM first identifies and structurally selects salient weights and minimizes the compression loss through an effective binary residual approximation strategy. Moreover considering the bell45;shaped distribution of the non45;salient weights we propose an optimal splitting search to group and binarize them accurately. BiLLM achieving for the first time high45;accuracy inference (e.g. 8.41 perplexity on LLaMA245;70B) with only 1.0845;bit weights across various LLMs families and evaluation metrics outperforms SOTA quantization methods of LLM by significant margins. Moreover BiLLM enables the binarization process of the LLM with 7 billion weights within 0.5 hours on a single GPU demonstrating satisfactory time efficiency. Our code is available at https://github.com/Aaronhuang&#45;778/BiLLM.
