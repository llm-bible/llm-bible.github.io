---
layout: publication
title: 'From Reflection To Perfection: Scaling Inference-time Optimization For Text-to-image Diffusion Models Via Reflection Tuning'
authors: Le Zhuo, Liangbing Zhao, Sayak Paul, Yue Liao, Renrui Zhang, Yi Xin, Peng Gao, Mohamed Elhoseiny, Hongsheng Li
conference: "Arxiv"
year: 2025
bibkey: zhuo2025from
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.16080'}
tags: ['Transformer', 'RAG', 'Efficiency and Optimization', 'Model Architecture', 'Tools', 'Training Techniques', 'Merging', 'Prompting', 'Multimodal Models', 'Pretraining Methods']
---
Recent text-to-image diffusion models achieve impressive visual quality
through extensive scaling of training data and model parameters, yet they often
struggle with complex scenes and fine-grained details. Inspired by the
self-reflection capabilities emergent in large language models, we propose
ReflectionFlow, an inference-time framework enabling diffusion models to
iteratively reflect upon and refine their outputs. ReflectionFlow introduces
three complementary inference-time scaling axes: (1) noise-level scaling to
optimize latent initialization; (2) prompt-level scaling for precise semantic
guidance; and most notably, (3) reflection-level scaling, which explicitly
provides actionable reflections to iteratively assess and correct previous
generations. To facilitate reflection-level scaling, we construct GenRef, a
large-scale dataset comprising 1 million triplets, each containing a
reflection, a flawed image, and an enhanced image. Leveraging this dataset, we
efficiently perform reflection tuning on state-of-the-art diffusion
transformer, FLUX.1-dev, by jointly modeling multimodal inputs within a unified
framework. Experimental results show that ReflectionFlow significantly
outperforms naive noise-level scaling methods, offering a scalable and
compute-efficient solution toward higher-quality image synthesis on challenging
tasks.
