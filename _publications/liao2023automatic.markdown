---
layout: publication
title: 'An Automatic Evaluation Framework For Multi-turn Medical Consultations Capabilities Of Large Language Models'
authors: Yusheng Liao, Yutong Meng, Hongcheng Liu, Yanfeng Wang, Yu Wang
conference: "Arxiv"
year: 2023
bibkey: liao2023automatic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.02077"}
tags: ['Fine-Tuning', 'Tools', 'Reinforcement Learning', 'Security', 'Training Techniques', 'Pretraining Methods']
---
Large language models (LLMs) have achieved significant success in interacting
with human. However, recent studies have revealed that these models often
suffer from hallucinations, leading to overly confident but incorrect
judgments. This limits their application in the medical domain, where tasks
require the utmost accuracy. This paper introduces an automated evaluation
framework that assesses the practical capabilities of LLMs as virtual doctors
during multi-turn consultations. Consultation tasks are designed to require
LLMs to be aware of what they do not know, to inquire about missing medical
information from patients, and to ultimately make diagnoses. To evaluate the
performance of LLMs for these tasks, a benchmark is proposed by reformulating
medical multiple-choice questions from the United States Medical Licensing
Examinations (USMLE), and comprehensive evaluation metrics are developed and
evaluated on three constructed test sets. A medical consultation training set
is further constructed to improve the consultation ability of LLMs. The results
of the experiments show that fine-tuning with the training set can alleviate
hallucinations and improve LLMs' performance on the proposed benchmark.
Extensive experiments and ablation studies are conducted to validate the
effectiveness and robustness of the proposed framework.
