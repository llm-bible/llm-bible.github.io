---
layout: publication
title: 'SECURA: Sigmoid-enhanced CUR Decomposition With Uninterrupted Retention And Low-rank Adaptation In Large Language Models'
authors: Yuxuan Zhang
conference: "Arxiv"
year: 2025
bibkey: zhang2025sigmoid
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.18168'}
tags: ['RAG', 'Efficiency and Optimization', 'Training Techniques', 'Tools', 'Fine-Tuning', 'Pretraining Methods']
---
With the rapid development of large language models (LLMs), fully fine-tuning
(FT) these models is becoming increasingly infeasible due to high computational
demands. Moreover, FT also increases the risk of catastrophic forgetting. As an
alternative, Low-Rank Adaptation (LoRA) has been proposed. By fine-tuning only
a small subset of parameters, LoRA achieves performance similar to FT while
significantly reducing resource requirements. However, since LoRA inherits FT's
design, the issue of catastrophic forgetting still remains. To address these
limitations, we propose SECURA: Sigmoid-Enhanced CUR Decomposition LoRA, a
novel PEFT variant designed to mitigate catastrophic forgetting while improving
fine-tuning performance. Our method introduces a novel normalization technique,
Sigmoid-based Magnitude Norm (S-MagNorm), which enhances parameter retention
and fine-tuning efficiency. SECURA has been evaluated on a diverse range of
tasks, including mathematical problem-solving (GSM8K), complex
question-answering (CNNDM), translation (NewsDE), and complex multiple-choice
reasoning (LogiQA). Experimental results demonstrate that it achieves an
average fine-tuning improvement of 3.59% across four MCQ tasks and 2.51% across
five QA tasks on Gemma2 2B, Qwen2 1.5B, Qwen2 7B, Llama3 8B, and Llama3.1 8B,
outperforming DoRA. Additionally, SECURA demonstrates superior knowledge
retention capabilities, achieving state-of-the-art performance in 16 continual
learning tests and maintaining more than 70% accuracy on LLMs' basic knowledge
compared to Experience Replay (ER), sequential learning (SEQ), EWC, I-LoRA, and
CUR-LoRA.
