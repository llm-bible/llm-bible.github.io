---
layout: publication
title: 'Deepseek-vl2: Mixture-of-experts Vision-language Models For Advanced Multimodal Understanding'
authors: Zhiyu Wu, Xiaokang Chen, Zizheng Pan, Xingchao Liu, Wen Liu, Damai Dai, Huazuo Gao, Yiyang Ma, Chengyue Wu, Bingxuan Wang, Zhenda Xie, Yu Wu, Kai Hu, Jiawei Wang, Yaofeng Sun, Yukun Li, Yishi Piao, Kang Guan, Aixin Liu, Xin Xie, Yuxiang You, Kai Dong, Xingkai Yu, Haowei Zhang, Liang Zhao, Yisong Wang, Chong Ruan
conference: "Arxiv"
year: 2024
bibkey: wu2024deepseek
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.10302'}
  - {name: "Code", url: 'https://github.com/deepseek-ai/DeepSeek-VL2'}
tags: ['Attention Mechanism', 'Has Code', 'RAG', 'Applications', 'Model Architecture', 'Multimodal Models']
---
We present DeepSeek-VL2, an advanced series of large Mixture-of-Experts (MoE)
Vision-Language Models that significantly improves upon its predecessor,
DeepSeek-VL, through two key major upgrades. For the vision component, we
incorporate a dynamic tiling vision encoding strategy designed for processing
high-resolution images with different aspect ratios. For the language
component, we leverage DeepSeekMoE models with the Multi-head Latent Attention
mechanism, which compresses Key-Value cache into latent vectors, to enable
efficient inference and high throughput. Trained on an improved vision-language
dataset, DeepSeek-VL2 demonstrates superior capabilities across various tasks,
including but not limited to visual question answering, optical character
recognition, document/table/chart understanding, and visual grounding. Our
model series is composed of three variants: DeepSeek-VL2-Tiny,
DeepSeek-VL2-Small and DeepSeek-VL2, with 1.0B, 2.8B and 4.5B activated
parameters respectively. DeepSeek-VL2 achieves competitive or state-of-the-art
performance with similar or fewer activated parameters compared to existing
open-source dense and MoE-based models. Codes and pre-trained models are
publicly accessible at https://github.com/deepseek-ai/DeepSeek-VL2.
