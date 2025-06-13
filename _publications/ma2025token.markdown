---
layout: publication
title: 'Token-shuffle: Towards High-resolution Image Generation With Autoregressive Models'
authors: Xu Ma, Peize Sun, Haoyu Ma, Hao Tang, Chih-yao Ma, Jialiang Wang, Kunpeng Li, Xiaoliang Dai, Yujun Shi, Xuan Ju, Yushi Hu, Artsiom Sanakoyeu, Felix Juefei-xu, Ji Hou, Junjiao Tian, Tao Xu, Tingbo Hou, Yen-cheng Liu, Zecheng He, Zijian He, Matt Feiszli, Peizhao Zhang, Peter Vajda, Sam Tsai, Yun Fu
conference: "Arxiv"
year: 2025
bibkey: ma2025token
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.17789"}
tags: ['Multimodal Models', 'Training Techniques', 'Efficiency and Optimization', 'Model Architecture', 'Reinforcement Learning', 'RAG', 'Language Modeling', 'GPT', 'Merging', 'Pretraining Methods', 'Transformer', 'Prompting']
---
Autoregressive (AR) models, long dominant in language generation, are
increasingly applied to image synthesis but are often considered less
competitive than Diffusion-based models. A primary limitation is the
substantial number of image tokens required for AR models, which constrains
both training and inference efficiency, as well as image resolution. To address
this, we present Token-Shuffle, a novel yet simple method that reduces the
number of image tokens in Transformer. Our key insight is the dimensional
redundancy of visual vocabularies in Multimodal Large Language Models (MLLMs),
where low-dimensional visual codes from visual encoder are directly mapped to
high-dimensional language vocabularies. Leveraging this, we consider two key
operations: token-shuffle, which merges spatially local tokens along channel
dimension to decrease the input token number, and token-unshuffle, which
untangles the inferred tokens after Transformer blocks to restore the spatial
arrangement for output. Jointly training with textual prompts, our strategy
requires no additional pretrained text-encoder and enables MLLMs to support
extremely high-resolution image synthesis in a unified next-token prediction
way while maintaining efficient training and inference. For the first time, we
push the boundary of AR text-to-image generation to a resolution of 2048x2048
with gratifying generation performance. In GenAI-benchmark, our 2.7B model
achieves 0.77 overall score on hard prompts, outperforming AR models LlamaGen
by 0.18 and diffusion models LDM by 0.15. Exhaustive large-scale human
evaluations also demonstrate our prominent image generation ability in terms of
text-alignment, visual flaw, and visual appearance. We hope that Token-Shuffle
can serve as a foundational design for efficient high-resolution image
generation within MLLMs.
