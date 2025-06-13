---
layout: publication
title: 'Gaussian Weight Sampling For Scalable, Efficient And Stable Pseudo-quantization Training'
authors: Myeonghwan Ahn, Sungjoo Yoo
conference: "Arxiv"
year: 2025
bibkey: ahn2025gaussian
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.11170"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'GPT', 'Quantization', 'Pre-Training']
---
Ever-growing scale of large language models (LLMs) is pushing for improved efficiency, favoring fully quantized training (FQT) over BF16. While FQT accelerates training, it faces consistency challenges and requires searching over an exponential number of cases, each needing over 200B tokens to ensure stability.
  Pseudo-quantization training (PQT) addresses the issues of FQT, although it is not well-studied. We explore the practical implications of PQT in detail and propose a noise distribution \\(R\\) that is floating-point (FP)-friendly, with ideal properties including stochastic precision annealing. As a result, the proposed method serves as an effective theoretical foundation for low-precision FP parameters through PQT, utilizing efficient fake quantization via an addition and subsequent FP casting.
  We demonstrate that Gaussian weight sampling is (1) scalable: supports low-precision FP parameters down to FP6 and high-precision noise up to 9-bit with BF16 operator. The proposed method is (2) efficient: incurring computational overhead as low as 1.40% on the A100 GPU in terms of Llama2 training tokens per second, and requiring 2 bytes per parameter in GPU memory. We demonstrate that PQT with Gaussian weight sampling is (3) stable: closely following or even surpassing performance of the BF16 baseline while pre-training GPT2 and Llama2 models with up to 1B parameters and 300B tokens.
