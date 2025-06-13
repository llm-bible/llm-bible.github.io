---
layout: publication
title: 'TCM-FTP: Fine-tuning Large Language Models For Herbal Prescription Prediction'
authors: Xingzhi Zhou, Xin Dong, Chunhao Li, Yuning Bai, Yulong Xu, Ka Chun Cheung, Simon See, Xinpeng Song, Runshun Zhang, Xuezhong Zhou, Nevin L. Zhang
conference: "Arxiv"
year: 2024
bibkey: zhou2024tcm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.10510"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'RAG', 'Pretraining Methods', 'Fine-Tuning']
---
Traditional Chinese medicine (TCM) has relied on specific combinations of
herbs in prescriptions to treat various symptoms and signs for thousands of
years. Predicting TCM prescriptions poses a fascinating technical challenge
with significant practical implications. However, this task faces limitations
due to the scarcity of high-quality clinical datasets and the complex
relationship between symptoms and herbs. To address these issues, we introduce
\textit\{DigestDS\}, a novel dataset comprising practical medical records from
experienced experts in digestive system diseases. We also propose a method,
TCM-FTP (TCM Fine-Tuning Pre-trained), to leverage pre-trained large language
models (LLMs) via supervised fine-tuning on \textit\{DigestDS\}. Additionally, we
enhance computational efficiency using a low-rank adaptation technique.
Moreover, TCM-FTP incorporates data augmentation by permuting herbs within
prescriptions, exploiting their order-agnostic nature. Impressively, TCM-FTP
achieves an F1-score of 0.8031, significantly outperforming previous methods.
Furthermore, it demonstrates remarkable accuracy in dosage prediction,
achieving a normalized mean square error of 0.0604. In contrast, LLMs without
fine-tuning exhibit poor performance. Although LLMs have demonstrated
wide-ranging capabilities, our work underscores the necessity of fine-tuning
for TCM prescription prediction and presents an effective way to accomplish
this.
