---
layout: publication
title: LUT45;GEMM Quantized Matrix Multiplication Based On Luts For Efficient Inference In Large45;scale Generative Language Models
authors: Park Gunho, Park Baeseong, Kim Minsub, Lee Sungjae, Kim Jeonghoon, Kwon Beomseok, Kwon Se Jung, Kim Byeongwook, Lee Youngjoo, Lee Dongsoo
conference: "Arxiv"
year: 2022
bibkey: park2022lut
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2206.09557"}
tags: ['Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Quantization', 'Transformer']
---
Recent advances in self45;supervised learning and the Transformer architecture have significantly improved natural language processing (NLP) achieving remarkably low perplexity. However the growing size of NLP models introduces a memory wall problem during the generation phase. To mitigate this issue recent efforts have focused on quantizing model weights to sub45;445;bit precision while preserving full precision for activations resulting in practical speed45;ups during inference on a single GPU. However these improvements primarily stem from reduced memory movement which necessitates a resource45;intensive dequantization process rather than actual computational reduction. In this paper we introduce LUT45;GEMM an efficient kernel for quantized matrix multiplication which not only eliminates the resource45;intensive dequantization process but also reduces computational costs compared to previous kernels for weight45;only quantization. Furthermore we proposed group45;wise quantization to offer a flexible trade45;off between compression ratio and accuracy. The impact of LUT45;GEMM is facilitated by implementing high compression ratios through low45;bit quantization and efficient LUT45;based operations. We show experimentally that when applied to the OPT45;175B model with 345;bit quantization LUT45;GEMM substantially accelerates token generation latency achieving a remarkable 2.1× improvement on a single GPU when compared to OPTQ which relies on the costly dequantization process.
