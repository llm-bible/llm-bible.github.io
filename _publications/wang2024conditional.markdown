---
layout: publication
title: 'C3LLM: Conditional Multimodal Content Generation Using Large Language Models'
authors: Wang Zixuan, Duan Qinkai, Tai Yu-wing, Tang Chi-keung
conference: "Arxiv"
year: 2024
bibkey: wang2024conditional
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.16136"}
tags: ['GPT', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Tools', 'Transformer']
---
We introduce C3LLM (Conditioned-on-Three-Modalities Large Language Models) a novel framework combining three tasks of video-to-audio audio-to-text and text-to-audio together. C3LLM adapts the Large Language Model (LLM) structure as a bridge for aligning different modalities synthesizing the given conditional information and making multimodal generation in a discrete manner. Our contributions are as follows. First we adapt a hierarchical structure for audio generation tasks with pre-trained audio codebooks. Specifically we train the LLM to generate audio semantic tokens from the given conditions and further use a non-autoregressive transformer to generate different levels of acoustic tokens in layers to better enhance the fidelity of the generated audio. Second based on the intuition that LLMs were originally designed for discrete tasks with the next-word prediction method we use the discrete representation for audio generation and compress their semantic meanings into acoustic tokens similar to adding acoustic vocabulary to LLM. Third our method combines the previous tasks of audio understanding video-to-audio generation and text-to-audio generation together into one unified model providing more versatility in an end-to-end fashion. Our C3LLM achieves improved results through various automated evaluation metrics providing better semantic alignment compared to previous methods.
