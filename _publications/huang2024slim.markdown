---
layout: publication
title: SliM-LLM Salience-Driven Mixed-Precision Quantization for Large Language Models
authors: Huang Wei, Qin Haotong, Liu Yangdong, Li Yawei, Liu Xianglong, Benini Luca, Magno Michele, Qi Xiaojuan
conference: "Arxiv"
year: 2024
bibkey: huang2024slim
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.14917"}
tags: ['Applications', 'Efficiency And Optimization', 'Quantization', 'Training Techniques']
---
Large language models (LLMs) achieve remarkable performance in natural language understanding but require substantial computation and memory resources. Post-training quantization (PTQ) is a powerful compression technique extensively investigated in LLMs. However existing PTQ methods are still not ideal in terms of accuracy and efficiency especially with below 4 bit-widths. Standard PTQ methods using group-wise quantization suffer difficulties in quantizing LLMs accurately to such low-bit but advanced methods remaining high-precision weights element-wisely are hard to realize their theoretical hardware efficiency. This paper presents a Salience-Driven Mixed-Precision Quantization scheme for LLMs namely SliM-LLM. The scheme exploits the salience distribution of weights to determine optimal bit-width and quantizers for accurate LLM quantization while aligning bit-width partition to groups for compact memory usage and fast integer inference. Specifically the proposed SliM-LLM mainly relies on two novel techniques (1) Salience-Determined Bit Allocation utilizes the clustering characteristics of salience distribution to allocate the bit-widths of each group increasing the accuracy of quantized LLMs and maintaining the inference efficiency; (2) Salience-Weighted Quantizer Calibration optimizes the parameters of the quantizer by considering the element-wise salience within the group balancing the maintenance of salient information and minimization of errors. Comprehensive experiments show that SliM-LLM significantly improves the accuracy of LLMs at ultra-low bits e.g. 2-bit LLaMA-7B achieves a 5.5-times memory-saving than original model on NVIDIA A800 GPUs and 48 decrease of perplexity compared to the state-of-the-art gradient-free PTQ method. Moreover SliM-LLM+ which is integrated from the extension of SliM-LLM with gradient-based quantizers further reduces perplexity by 35.1.
