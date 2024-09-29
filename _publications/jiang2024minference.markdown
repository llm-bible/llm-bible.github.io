---
layout: publication
title: Minference 1.0 Accelerating Pre45;filling For Long45;context Llms Via Dynamic Sparse Attention
authors: Jiang Huiqiang, Li Yucheng, Zhang Chengruidong, Wu Qianhui, Luo Xufang, Ahn Surin, Han Zhenhua, Abdi Amir H., Li Dongsheng, Lin Chin-yew, Yang Yuqing, Qiu Lili
conference: "Arxiv"
year: 2024
bibkey: jiang2024minference
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.02490"}
  - {name: "Code", url: "https://aka.ms/MInference"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Has Code', 'Model Architecture', 'Prompting', 'RAG', 'Training Techniques']
---
The computational challenges of Large Language Model (LLM) inference remain a significant barrier to their widespread deployment especially as prompt lengths continue to increase. Due to the quadratic complexity of the attention computation it takes 30 minutes for an 8B LLM to process a prompt of 1M tokens (i.e. the pre45;filling stage) on a single A100 GPU. Existing methods for speeding up prefilling often fail to maintain acceptable accuracy or efficiency when applied to long45;context LLMs. To address this gap we introduce MInference (Milliontokens Inference) a sparse calculation method designed to accelerate pre45;filling of long45;sequence processing. Specifically we identify three unique patterns in long45;context attention matrices45;the A45;shape Vertical45;Slash and Block45;Sparsethat can be leveraged for efficient sparse computation on GPUs. We determine the optimal pattern for each attention head offline and dynamically build sparse indices based on the assigned pattern during inference. With the pattern and sparse indices we perform efficient sparse attention calculations via our optimized GPU kernels to significantly reduce the latency in the pre45;filling stage of long45;context LLMs. Our proposed technique can be directly applied to existing LLMs without any modifications to the pre45;training setup or additional fine45;tuning. By evaluating on a wide range of downstream tasks including InfiniteBench RULER PG45;19 and Needle In A Haystack and models including LLaMA45;345;1M GLM445;1M Yi45;200K Phi45;345;128K and Qwen245;128K we demonstrate that MInference effectively reduces inference latency by up to 10x for pre45;filling on an A100 while maintaining accuracy. Our code is available at https://aka.ms/MInference.
