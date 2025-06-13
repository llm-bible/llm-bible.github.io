---
layout: publication
title: 'A Lora-based Approach To Fine-tuning Llms For Educational Guidance In Resource-constrained Settings'
authors: Md Millat Hosen
conference: "Arxiv"
year: 2025
bibkey: hosen2025lora
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.15610"}
tags: ['Fine-Tuning', 'Tools', 'GPT', 'Efficiency and Optimization', 'Ethics and Bias', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods', 'Quantization']
---
The current study describes a cost-effective method for adapting large
language models (LLMs) for academic advising with study-abroad contexts in mind
and for application in low-resource methods for acculturation. With the
Mistral-7B-Instruct model applied with a Low-Rank Adaptation (LoRA) method and
a 4-bit quantization method, the model underwent training in two distinct
stages related to this study's purpose to enhance domain specificity while
maintaining computational efficiency. In Phase 1, the model was conditioned
with a synthetic dataset via the Gemini Pro API, and in Phase 2, it was trained
with manually curated datasets from the StudyAbroadGPT project to achieve
enhanced, contextualized responses. Technical innovations entailed
memory-efficient quantization, parameter-efficient adaptation, and continuous
training analytics via Weights & Biases. After training, this study
demonstrated a reduction in training loss by 52.7%, 92% accuracy in
domain-specific recommendations, achieved 95% markdown-based formatting
support, and a median run-rate of 100 samples per second on off-the-shelf GPU
equipment. These findings support the effective application of
instruction-tuned LLMs within educational advisers, especially in low-resource
institutional scenarios. Limitations included decreased generalizability and
the application of a synthetically generated dataset, but this framework is
scalable for adding new multilingual-augmented and real-time academic advising
processes. Future directions may include plans for the integration of
retrieval-augmented generation, applying dynamic quantization routines, and
connecting to real-time academic databases to increase adaptability and
accuracy.
