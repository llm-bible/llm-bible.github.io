---
layout: publication
title: Squeezellm Dense45;and45;sparse Quantization
authors: Kim Sehoon, Hooper Coleman, Gholami Amir, Dong Zhen, Li Xiuyu, Shen Sheng, Mahoney Michael W., Keutzer Kurt
conference: "Arxiv"
year: 2023
bibkey: kim2023dense
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.07629"}
  - {name: "Code", url: "https://github.com/SqueezeAILab/SqueezeLLM"}
tags: ['Efficiency And Optimization', 'Has Code', 'Quantization', 'Tools', 'Training Techniques']
---
Generative Large Language Models (LLMs) have demonstrated remarkable results for a wide range of tasks. However deploying these models for inference has been a significant challenge due to their unprecedented resource requirements. This has forced existing deployment frameworks to use multi45;GPU inference pipelines which are often complex and costly or to use smaller and less performant models. In this work we demonstrate that the main bottleneck for generative inference with LLMs is memory bandwidth rather than compute specifically for single batch inference. While quantization has emerged as a promising solution by representing weights with reduced precision previous efforts have often resulted in notable performance degradation. To address this we introduce SqueezeLLM a post45;training quantization framework that not only enables lossless compression to ultra45;low precisions of up to 345;bit but also achieves higher quantization performance under the same memory constraint. Our framework incorporates two novel ideas (i) sensitivity45;based non45;uniform quantization which searches for the optimal bit precision assignment based on second45;order information; and (ii) the Dense45;and45;Sparse decomposition that stores outliers and sensitive weight values in an efficient sparse format. When applied to the LLaMA models our 345;bit quantization significantly reduces the perplexity gap from the FP16 baseline by up to 2.1x as compared to the state45;of45;the45;art methods with the same memory requirement. Furthermore when deployed on an A6000 GPU our quantized models achieve up to 2.3x speedup compared to the baseline. Our code is available at https://github.com/SqueezeAILab/SqueezeLLM.
