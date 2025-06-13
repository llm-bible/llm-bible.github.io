---
layout: publication
title: 'Speech Translation Refinement Using Large Language Models'
authors: Huaixia Dou, Xinyu Tian, Xinglin Lyu, Jie Zhu, Junhui Li, Lifan Guo
conference: "Arxiv"
year: 2025
bibkey: dou2025speech
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.15090"}
tags: ['Training Techniques', 'Model Architecture', 'GPT', 'Pretraining Methods', 'Fine-Tuning', 'Prompting', 'In-Context Learning', 'INTERSPEECH']
---
Recent advancements in large language models (LLMs) have demonstrated their
remarkable capabilities across various language tasks. Inspired by the success
of text-to-text translation refinement, this paper investigates how LLMs can
improve the performance of speech translation by introducing a joint refinement
process. Through the joint refinement of speech translation (ST) and automatic
speech recognition (ASR) transcription via LLMs, the performance of the ST
model is significantly improved in both training-free in-context learning and
parameter-efficient fine-tuning scenarios. Additionally, we explore the effect
of document-level context on refinement under the context-aware fine-tuning
scenario. Experimental results on the MuST-C and CoVoST 2 datasets, which
include seven translation tasks, demonstrate the effectiveness of the proposed
approach using several popular LLMs including GPT-3.5-turbo, LLaMA3-8B, and
Mistral-12B. Further analysis further suggests that jointly refining both
transcription and translation yields better performance compared to refining
translation alone. Meanwhile, incorporating document-level context
significantly enhances refinement performance. We release our code and datasets
on GitHub.
