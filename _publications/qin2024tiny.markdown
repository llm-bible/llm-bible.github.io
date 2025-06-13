---
layout: publication
title: 'Tiny-align: Bridging Automatic Speech Recognition And Large Language Model On The Edge'
authors: Ruiyang Qin, Dancheng Liu, Gelei Xu, Zheyu Yan, Chenhui Xu, Yuting Hu, X. Sharon Hu, Jinjun Xiong, Yiyu Shi
conference: "Arxiv"
year: 2024
bibkey: qin2024tiny
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.13766'}
tags: ['INTERSPEECH', 'Training Techniques', 'Tools', 'Fine-Tuning', 'Multimodal Models', 'Pretraining Methods']
---
The combination of Large Language Models (LLM) and Automatic Speech
Recognition (ASR), when deployed on edge devices (called edge ASR-LLM), can
serve as a powerful personalized assistant to enable audio-based interaction
for users. Compared to text-based interaction, edge ASR-LLM allows accessible
and natural audio interactions. Unfortunately, existing ASR-LLM models are
mainly trained in high-performance computing environments and produce
substantial model weights, making them difficult to deploy on edge devices.
More importantly, to better serve users' personalized needs, the ASR-LLM must
be able to learn from each distinct user, given that audio input often contains
highly personalized characteristics that necessitate personalized on-device
training. Since individually fine-tuning the ASR or LLM often leads to
suboptimal results due to modality-specific limitations, end-to-end training
ensures seamless integration of audio features and language understanding
(cross-modal alignment), ultimately enabling a more personalized and efficient
adaptation on edge devices. However, due to the complex training requirements
and substantial computational demands of existing approaches, cross-modal
alignment between ASR audio and LLM can be challenging on edge devices. In this
work, we propose a resource-efficient cross-modal alignment framework that
bridges ASR and LLMs on edge devices to handle personalized audio input. Our
framework enables efficient ASR-LLM alignment on resource-constrained devices
like NVIDIA Jetson Orin (8GB RAM), achieving 50x training time speedup while
improving the alignment quality by more than 50%. To the best of our
knowledge, this is the first work to study efficient ASR-LLM alignment on
resource-constrained edge devices.
