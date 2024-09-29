---
layout: publication
title: MAGVLT Masked Generative Vision45;and45;language Transformer
authors: Kim Sungwoong, Jo Daejin, Lee Donghoon, Kim Jongmin
conference: "Arxiv"
year: 2023
bibkey: kim2023masked
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2303.12208"}
tags: ['Efficiency And Optimization', 'GPT', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
While generative modeling on multimodal image45;text data has been actively developed with large45;scale paired datasets there have been limited attempts to generate both image and text data by a single model rather than a generation of one fixed modality conditioned on the other modality. In this paper we explore a unified generative vision45;and45;language (VL) model that can produce both images and text sequences. Especially we propose a generative VL transformer based on the non45;autoregressive mask prediction named MAGVLT and compare it with an autoregressive generative VL transformer (ARGVLT). In comparison to ARGVLT the proposed MAGVLT enables bidirectional context encoding fast decoding by parallel token predictions in an iterative refinement and extended editing capabilities such as image and text infilling. For rigorous training of our MAGVLT with image45;text pairs from scratch we combine the image45;to45;text text45;to45;image and joint image45;and45;text mask prediction tasks. Moreover we devise two additional tasks based on the step45;unrolled mask prediction and the selective prediction on the mixture of two image45;text pairs. Experimental results on various downstream generation tasks of VL benchmarks show that our MAGVLT outperforms ARGVLT by a large margin even with significant inference speedup. Particularly MAGVLT achieves competitive results on both zero45;shot image45;to45;text and text45;to45;image generation tasks from MS45;COCO by one moderate45;sized model (fewer than 500M parameters) even without the use of monomodal data and networks.
