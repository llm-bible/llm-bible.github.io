---
layout: publication
title: 'RWKV-CLIP: A Robust Vision-language Representation Learner'
authors: Gu Tiancheng, Yang Kaicheng, An Xiang, Feng Ziyong, Liu Dongnan, Cai Weidong, Deng Jiankang
conference: "Arxiv"
year: 2024
bibkey: gu2024rwkv
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.06973"}
  - {name: "Code", url: "https://github.com/deepglint/RWKV-CLIP"}
tags: ['Has Code', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'RAG', 'Tools', 'Training Techniques', 'Transformer']
---
Contrastive Language-Image Pre-training (CLIP) has significantly improved
performance in various vision-language tasks by expanding the dataset with
image-text pairs obtained from websites. This paper further explores CLIP from
the perspectives of data and model architecture. To address the prevalence of
noisy data and enhance the quality of large-scale image-text data crawled from
the internet, we introduce a diverse description generation framework that can
leverage Large Language Models (LLMs) to synthesize and refine content from
web-based texts, synthetic captions, and detection tags. Furthermore, we
propose RWKV-CLIP, the first RWKV-driven vision-language representation
learning model that combines the effective parallel training of transformers
with the efficient inference of RNNs. Comprehensive experiments across various
model scales and pre-training datasets demonstrate that RWKV-CLIP is a robust
and efficient vision-language representation learner, it achieves
state-of-the-art performance in several downstream tasks, including linear
probe, zero-shot classification, and zero-shot image-text retrieval. To
facilitate future research, the code and pre-trained models are released at
https://github.com/deepglint/RWKV-CLIP
