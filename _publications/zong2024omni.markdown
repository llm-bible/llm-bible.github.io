---
layout: publication
title: 'Easyref: Omni-generalized Group Image Reference For Diffusion Models Via Multimodal LLM'
authors: Zhuofan Zong, Dongzhi Jiang, Bingqi Ma, Guanglu Song, Hao Shao, Dazhong Shen, Yu Liu, Hongsheng Li
conference: "Arxiv"
year: 2024
bibkey: zong2024omni
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.09618'}
tags: ['RAG', 'Training Techniques', 'Merging', 'Fine-Tuning', 'Prompting', 'Multimodal Models']
---
Significant achievements in personalization of diffusion models have been
witnessed. Conventional tuning-free methods mostly encode multiple reference
images by averaging their image embeddings as the injection condition, but such
an image-independent operation cannot perform interaction among images to
capture consistent visual elements within multiple references. Although the
tuning-based Low-Rank Adaptation (LoRA) can effectively extract consistent
elements within multiple images through the training process, it necessitates
specific finetuning for each distinct image group. This paper introduces
EasyRef, a novel plug-and-play adaptation method that enables diffusion models
to be conditioned on multiple reference images and the text prompt. To
effectively exploit consistent visual elements within multiple images, we
leverage the multi-image comprehension and instruction-following capabilities
of the multimodal large language model (MLLM), prompting it to capture
consistent visual elements based on the instruction. Besides, injecting the
MLLM's representations into the diffusion process through adapters can easily
generalize to unseen domains, mining the consistent visual elements within
unseen data. To mitigate computational costs and enhance fine-grained detail
preservation, we introduce an efficient reference aggregation strategy and a
progressive training scheme. Finally, we introduce MRBench, a new
multi-reference image generation benchmark. Experimental results demonstrate
EasyRef surpasses both tuning-free methods like IP-Adapter and tuning-based
methods like LoRA, achieving superior aesthetic quality and robust zero-shot
generalization across diverse domains.
