---
layout: publication
title: 'Easygen: Easing Multimodal Generation With Bidiffuser And Llms'
authors: Zhao Xiangyu, Liu Bo, Liu Qijiong, Shi Guangyuan, Wu Xiao-ming
conference: "Arxiv"
year: 2023
bibkey: zhao2023easing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.08949"}
  - {name: "Code", url: "https://github.com/zxy556677/EasyGen"}
tags: ['Applications', 'Has Code', 'Language Modeling', 'Merging', 'Multimodal Models', 'RAG', 'Training Techniques']
---
We present EasyGen, an efficient model designed to enhance multimodal understanding and generation by harnessing the capabilities of diffusion models and large language models (LLMs), Unlike existing multimodal models that predominately depend on encoders like CLIP or ImageBind and need ample amounts of training data to bridge modalities,EasyGen leverages BiDiffuser,a bidirectional conditional diffusion model, to foster more efficient modality interactions. Easygen achieves text generation by training a projection layer linking BiDiffuser and an LLM, and facilities image generation by training an adapter to align the LLM's text space with the BiDiffuser's image space, Comprehensive quantitative and qualitative experiments show that EasyGen excels in data-efficient training, high-quality image generation, and extendibility, effectively addressing the challenges in multimodal generation. The source code is available at https://github.com/zxy556677/EasyGen.
