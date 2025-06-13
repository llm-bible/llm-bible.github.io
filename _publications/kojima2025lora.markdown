---
layout: publication
title: 'Lora-ttt: Low-rank Test-time Training For Vision-language Models'
authors: Yuto Kojima, Jiarui Xu, Xueyan Zou, Xiaolong Wang
conference: "Arxiv"
year: 2025
bibkey: kojima2025lora
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.02069"}
tags: ['Fine-Tuning', 'Tools', 'RAG', 'Training Techniques', 'Multimodal Models', 'Prompting']
---
The rapid advancements in vision-language models (VLMs), such as CLIP, have
intensified the need to address distribution shifts between training and
testing datasets. Although prior Test-Time Training (TTT) techniques for VLMs
have demonstrated robust performance, they predominantly rely on tuning text
prompts, a process that demands substantial computational resources and is
heavily dependent on entropy-based loss. In this paper, we propose LoRA-TTT, a
novel TTT method that leverages Low-Rank Adaptation (LoRA), applied exclusively
to the image encoder of VLMs. By introducing LoRA and updating only its
parameters during test time, our method offers a simple yet effective TTT
approach, retaining the model's initial generalization capability while
achieving substantial performance gains with minimal memory and runtime
overhead. Additionally, we introduce a highly efficient reconstruction loss
tailored for TTT. Our method can adapt to diverse domains by combining these
two losses, without increasing memory consumption or runtime. Extensive
experiments on two benchmarks, covering 15 datasets, demonstrate that our
method improves the zero-shot top-1 accuracy of CLIP-ViT-B/16 by an average of
5.79% on the OOD benchmark and 1.36% on the fine-grained benchmark, efficiently
surpassing test-time prompt tuning, without relying on any external models or
cache.
