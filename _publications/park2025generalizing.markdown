---
layout: publication
title: 'Generalizing From SIMPLE To HARD Visual Reasoning: Can We Mitigate Modality Imbalance In Vlms?'
authors: Simon Park, Abhishek Panigrahi, Yun Cheng, Dingli Yu, Anirudh Goyal, Sanjeev Arora
conference: "Arxiv"
year: 2025
bibkey: park2025generalizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.02669"}
tags: ['Training Techniques', 'Applications', 'Tools']
---
Vision Language Models (VLMs) are impressive at visual question answering and image captioning. But they underperform on multi-step visual reasoning -- even compared to LLMs on the same tasks presented in text form -- giving rise to perceptions of modality imbalance or brittleness. Towards a systematic study of such issues, we introduce a synthetic framework for assessing the ability of VLMs to perform algorithmic visual reasoning, comprising three tasks: Table Readout, Grid Navigation, and Visual Analogy. Each has two levels of difficulty, SIMPLE and HARD, and even the SIMPLE versions are difficult for frontier VLMs. We propose strategies for training on the SIMPLE version of tasks that improve performance on the corresponding HARD task, i.e., simple-to-hard (S2H) generalization. This controlled setup, where each task also has an equivalent text-only version, allows a quantification of the modality imbalance and how it is impacted by training strategy. We show that 1) explicit image-to-text conversion is important in promoting S2H generalization on images, by transferring reasoning from text; 2) conversion can be internalized at test time. We also report results of mechanistic study of this phenomenon. We identify measures of gradient alignment that can identify training strategies that promote better S2H generalization. Ablations highlight the importance of chain-of-thought.
