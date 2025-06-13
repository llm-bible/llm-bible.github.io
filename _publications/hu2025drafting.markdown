---
layout: publication
title: 'DREAM: Drafting With Refined Target Features And Entropy-adaptive Cross-attention Fusion For Multimodal Speculative Decoding'
authors: Yunhai Hu, Tianhua Xia, Zining Liu, Rahul Raman, Xingyu Liu, Bo Bao, Eric Sather, Vithursan Thangarasa, Sai Qian Zhang
conference: "Arxiv"
year: 2025
bibkey: hu2025drafting
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.19201'}
  - {name: "Code", url: 'https://github.com/SAI-Lab-NYU/DREAM.git'}
tags: ['Attention Mechanism', 'Has Code', 'Model Architecture', 'Tools', 'Training Techniques', 'GPT', 'Merging', 'Multimodal Models', 'Pretraining Methods']
---
Speculative decoding (SD) has emerged as a powerful method for accelerating autoregressive generation in large language models (LLMs), yet its integration into vision-language models (VLMs) remains underexplored. We introduce DREAM, a novel speculative decoding framework tailored for VLMs that combines three key innovations: (1) a cross-attention-based mechanism to inject intermediate features from the target model into the draft model for improved alignment, (2) adaptive intermediate feature selection based on attention entropy to guide efficient draft model training, and (3) visual token compression to reduce draft model latency. DREAM enables efficient, accurate, and parallel multimodal decoding with significant throughput improvement. Experiments across a diverse set of recent popular VLMs, including LLaVA, Pixtral, SmolVLM and Gemma3, demonstrate up to 3.6x speedup over conventional decoding and significantly outperform prior SD baselines in both inference throughput and speculative draft acceptance length across a broad range of multimodal benchmarks. The code is publicly available at: https://github.com/SAI-Lab-NYU/DREAM.git
