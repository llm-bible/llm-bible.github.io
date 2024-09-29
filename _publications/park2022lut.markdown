---
layout: publication
title: LUT-GEMM Quantized Matrix Multiplication Based On Luts For Efficient Inference In Large-scale Generative Language Models
authors: Park Gunho, Park Baeseong, Kim Minsub, Lee Sungjae, Kim Jeonghoon, Kwon Beomseok, Kwon Se Jung, Kim Byeongwook, Lee Youngjoo, Lee Dongsoo
conference: "Arxiv"
year: 2022
bibkey: park2022lut
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2206.09557"}
tags: ['Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Quantization', 'Training Techniques', 'Transformer']
---
Recent advances in self-supervised learning and the Transformer architecture have significantly improved natural language processing (NLP) achieving remarkably low perplexity. However the growing size of NLP models introduces a memory wall problem during the generation phase. To mitigate this issue recent efforts have focused on quantizing model weights to sub-4-bit precision while preserving full precision for activations resulting in practical speed-ups during inference on a single GPU. However these improvements primarily stem from reduced memory movement which necessitates a resource-intensive dequantization process rather than actual computational reduction. In this paper we introduce LUT-GEMM an efficient kernel for quantized matrix multiplication which not only eliminates the resource-intensive dequantization process but also reduces computational costs compared to previous kernels for weight-only quantization. Furthermore we proposed group-wise quantization to offer a flexible trade-off between compression ratio and accuracy. The impact of LUT-GEMM is facilitated by implementing high compression ratios through low-bit quantization and efficient LUT-based operations. We show experimentally that when applied to the OPT-175B model with 3-bit quantization LUT-GEMM substantially accelerates token generation latency achieving a remarkable 2.1× improvement on a single GPU when compared to OPTQ which relies on the costly dequantization process.
