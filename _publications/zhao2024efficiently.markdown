---
layout: publication
title: Efficiently Training 7B LLM with 1 Million Sequence Length on 8 GPUs
authors: Zhao Pinxue, Zhang Hailin, Fu Fangcheng, Nie Xiaonan, Liu Qibin, Yang Fang, Peng Yuanbo, Jiao Dian, Li Shuaipeng, Xue Jinbao, Tao Yangyu, Cui Bin
conference: "Arxiv"
year: 2024
bibkey: zhao2024efficiently
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.12117"}
tags: ['ARXIV', 'Applications', 'LLM', 'Transformer']
---
Nowadays Large Language Models (LLMs) have been trained using extended context lengths to foster more creative applications. However long context training poses great challenges considering the constraint of GPU memory. It not only leads to substantial activation memory consumption during training but also incurs considerable memory fragmentation. To facilitate long context training existing frameworks have adopted strategies such as recomputation and various forms of parallelisms. Nevertheless these techniques rely on redundant computation or extensive communication resulting in low Model FLOPS Utilization (MFU). In this paper we propose MEMO a novel LLM training framework designed for fine-grained activation memory management. Given the quadratic scaling of computation and linear scaling of memory with sequence lengths when using FlashAttention we offload memory-consuming activations to CPU memory after each layers forward pass and fetch them during the backward pass. To maximize the swapping of activations without hindering computation and to avoid exhausting limited CPU memory we implement a token-wise activation recomputation and swapping mechanism. Furthermore we tackle the memory fragmentation issue by employing a bi-level Mixed Integer Programming (MIP) approach optimizing the reuse of memory across transformer layers. Empirical results demonstrate that MEMO achieves an average of 2.42x and 2.26x MFU compared to Megatron-LM and DeepSpeed respectively. This improvement is attributed to MEMOs ability to minimize memory fragmentation reduce recomputation and intensive communication and circumvent the delays associated with the memory reorganization process due to fragmentation. By leveraging fine-grained activation memory management MEMO facilitates efficient training of 7B LLM with 1 million sequence length on just 8 A800 GPUs achieving an MFU of 52.30.
