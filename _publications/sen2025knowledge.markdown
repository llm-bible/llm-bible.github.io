---
layout: publication
title: 'Knowledge Distillation Of Domain-adapted Llms For Question-answering In Telecom'
authors: Rishika Sen, Sujoy Roychowdhury, Sumit Soman, H. G. Ranjani, Srikhetra Mohanty
conference: "Arxiv"
year: 2025
bibkey: sen2025knowledge
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.20000"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Distillation', 'Pretraining Methods', 'Fine-Tuning']
---
Knowledge Distillation (KD) is one of the approaches to reduce the size of
Large Language Models (LLMs). A LLM with smaller number of model parameters
(student) is trained to mimic the performance of a LLM of a larger size
(teacher model) on a specific task. For domain-specific tasks, it is not clear
if teacher or student model, or both, must be considered for domain adaptation.
In this work, we study this problem from perspective of telecom domain
Question-Answering (QA) task. We systematically experiment with Supervised
Fine-tuning (SFT) of teacher only, SFT of student only and SFT of both prior to
KD. We design experiments to study the impact of vocabulary (same and
different) and KD algorithms (vanilla KD and Dual Space KD, DSKD) on the
distilled model. Multi-faceted evaluation of the distillation using 14
different metrics (N-gram, embedding and LLM-based metrics) is considered.
Experimental results show that SFT of teacher improves performance of distilled
model when both models have same vocabulary, irrespective of algorithm and
metrics. Overall, SFT of both teacher and student results in better performance
across all metrics, although the statistical significance of the same depends
on the vocabulary of the teacher models.
