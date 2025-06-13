---
layout: publication
title: 'Thought2text: Text Generation From EEG Signal Using Large Language Models (llms)'
authors: Abhijit Mishra, Shreya Shukla, Jose Torres, Jacek Gwizdka, Shounak Roychowdhury
conference: "Arxiv"
year: 2024
bibkey: mishra2024text
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.07507"}
tags: ['Multimodal Models', 'Training Techniques', 'Language Modeling', 'Pretraining Methods', 'Fine-Tuning', 'Applications']
---
Decoding and expressing brain activity in a comprehensible form is a
challenging frontier in AI. This paper presents Thought2Text, which uses
instruction-tuned Large Language Models (LLMs) fine-tuned with EEG data to
achieve this goal. The approach involves three stages: (1) training an EEG
encoder for visual feature extraction, (2) fine-tuning LLMs on image and text
data, enabling multimodal description generation, and (3) further fine-tuning
on EEG embeddings to generate text directly from EEG during inference.
Experiments on a public EEG dataset collected for six subjects with image
stimuli and text captions demonstrate the efficacy of multimodal LLMs
(LLaMA-v3, Mistral-v0.3, Qwen2.5), validated using traditional language
generation evaluation metrics, as well as fluency and adequacy measures. This
approach marks a significant advancement towards portable, low-cost
"thoughts-to-text" technology with potential applications in both neuroscience
and natural language processing.
