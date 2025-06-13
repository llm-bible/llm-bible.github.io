---
layout: publication
title: 'Fork-merge Decoding: Enhancing Multimodal Understanding In Audio-visual Large Language Models'
authors: Chaeyoung Jung, Youngjoon Jang, Jongmin Choi, Joon Son Chung
conference: "Arxiv"
year: 2025
bibkey: jung2025fork
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.20873"}
tags: ['Ethics and Bias', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Multimodal Models']
---
The goal of this work is to enhance balanced multimodal understanding in audio-visual large language models (AV-LLMs) by addressing modality bias without requiring additional training. In current AV-LLMs, audio and video features are typically processed jointly in the decoder. While this strategy facilitates unified multimodal understanding, it may introduce modality bias, where the model tends to over-rely on one modality due to imbalanced training signals. To mitigate this, we propose Fork-Merge Decoding (FMD), a simple yet effective inference-time strategy that requires no additional training or architectural modifications. FMD first performs modality-specific reasoning by processing audio-only and video-only inputs through the early decoder layers (a fork phase), and then merges the resulting hidden states for joint reasoning in the remaining layers (a merge phase). This approach promotes balanced modality contributions and leverages complementary information across modalities. We evaluate our method on two representative AV-LLMs, VideoLLaMA2 and video-SALMONN, using three benchmark datasets. Experimental results demonstrate consistent performance improvements on tasks focused on audio, video, and combined audio-visual reasoning, demonstrating the effectiveness of inference-time interventions for robust multimodal understanding.
