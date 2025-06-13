---
layout: publication
title: 'Llava-ultra: Large Chinese Language And Vision Assistant For Ultrasound'
authors: Xuechen Guo, Wenhao Chai, Shi-yan Li, Gaoang Wang
conference: "Arxiv"
year: 2024
bibkey: guo2024llava
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.15074"}
tags: ['Security', 'Model Architecture', 'Efficiency and Optimization', 'Multimodal Models', 'RAG', 'Distillation', 'Merging', 'Fine-Tuning', 'Applications', 'Attention Mechanism']
---
Multimodal Large Language Model (MLLM) has recently garnered attention as a
prominent research focus. By harnessing powerful LLM, it facilitates a
transition of conversational generative AI from unimodal text to performing
multimodal tasks. This boom begins to significantly impact medical field.
However, general visual language model (VLM) lacks sophisticated comprehension
for medical visual question answering (Med-VQA). Even models specifically
tailored for medical domain tend to produce vague answers with weak visual
relevance. In this paper, we propose a fine-grained adaptive VLM architecture
for Chinese medical visual conversations through parameter-efficient tuning.
Specifically, we devise a fusion module with fine-grained vision encoders to
achieve enhancement for subtle medical visual semantics. Then we note data
redundancy common to medical scenes is ignored in most prior works. In cases of
a single text paired with multiple figures, we utilize weighted scoring with
knowledge distillation to adaptively screen valid images mirroring text
descriptions. For execution, we leverage a large-scale multimodal Chinese
ultrasound dataset obtained from the hospital. We create instruction-following
data based on text from professional doctors, which ensures effective tuning.
With enhanced model and quality data, our Large Chinese Language and Vision
Assistant for Ultrasound (LLaVA-Ultra) shows strong capability and robustness
to medical scenarios. On three Med-VQA datasets, LLaVA-Ultra surpasses previous
state-of-the-art models on various metrics.
