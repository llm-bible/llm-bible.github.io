---
layout: publication
title: 'Llasa: Scaling Train-time And Inference-time Compute For Llama-based Speech Synthesis'
authors: Zhen Ye, Xinfa Zhu, Chi-min Chan, Xinsheng Wang, Xu Tan, Jiahe Lei, Yi Peng, Haohe Liu, Yizhu Jin, Zheqi Dai, Hongzhan Lin, Jianyi Chen, Xingjian Du, Liumeng Xue, Yunlin Chen, Zhifei Li, Lei Xie, Qiuqiang Kong, Yike Guo, Wei Xue
conference: "Arxiv"
year: 2025
bibkey: ye2025scaling
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.04128'}
tags: ['Transformer', 'RAG', 'Model Architecture', 'Training Techniques', 'Tools', 'GPT', 'Merging', 'Reinforcement Learning', 'Pretraining Methods']
---
Recent advances in text-based large language models (LLMs), particularly in
the GPT series and the o1 model, have demonstrated the effectiveness of scaling
both training-time and inference-time compute. However, current
state-of-the-art TTS systems leveraging LLMs are often multi-stage, requiring
separate models (e.g., diffusion models after LLM), complicating the decision
of whether to scale a particular model during training or testing. This work
makes the following contributions: First, we explore the scaling of train-time
and inference-time compute for speech synthesis. Second, we propose a simple
framework Llasa for speech synthesis that employs a single-layer vector
quantizer (VQ) codec and a single Transformer architecture to fully align with
standard LLMs such as Llama. Our experiments reveal that scaling train-time
compute for Llasa consistently improves the naturalness of synthesized speech
and enables the generation of more complex and accurate prosody patterns.
Furthermore, from the perspective of scaling inference-time compute, we employ
speech understanding models as verifiers during the search, finding that
scaling inference-time compute shifts the sampling modes toward the preferences
of specific verifiers, thereby improving emotional expressiveness, timbre
consistency, and content accuracy. In addition, we released the checkpoint and
training code for our TTS model (1B, 3B, 8B) and codec model publicly
available.
