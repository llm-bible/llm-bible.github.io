---
layout: publication
title: 'Knowledge Distillation Using Frontier Open-source Llms: Generalizability And The Role Of Synthetic Data'
authors: Anup Shirgaonkar, Nikhil Pandey, Nazmiye Ceren Abay, Tolga Aktas, Vijay Aski
conference: "Arxiv"
year: 2024
bibkey: shirgaonkar2024knowledge
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.18588"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Distillation', 'Pretraining Methods', 'Fine-Tuning', 'Applications']
---
Leading open-source large language models (LLMs) such as
Llama-3.1-Instruct-405B are extremely capable at generating text, answering
questions, and solving a variety of natural language understanding tasks.
However, they incur higher inference cost and latency compared to smaller LLMs.
Knowledge distillation provides a way to use outputs from these large, capable
teacher models to train smaller student models which can be used for inference
at lower cost and latency, while retaining comparable accuracy. We investigate
the efficacy of distillation using the Llama-3.1-405B-Instruct teacher and the
smaller Llama-3.1-8B-Instruct and Llama-3.1-70B-Instruct student models.
Contributions of this work include (a) We evaluate the generalizability of
distillation with the above Llama-3.1 teacher-student pairs across different
tasks and datasets (b) We show that using synthetic data during distillation
significantly improves the accuracy of 8B and 70B models, and when used with
reasoning chains, even matches or surpasses the zero-shot accuracy of 405B
model on some datasets (c) We empirically show that distillation enables 8B and
70B models to internalize 405B's reasoning ability by using only standard
fine-tuning (without customizing any loss function). This allows cost and
latency-efficient student model inference. (d) We show pitfalls in evaluation
of distillation, and present task-specific evaluation, including both human and
LLM-grading, and ground-truth based traditional accuracy benchmarks. This
methodical study brings out the fundamental importance of synthetic data
quality in knowledge distillation, and of combining multiple, task-specific
ways of accuracy and quality evaluation in assessing the effectiveness of
distillation.
