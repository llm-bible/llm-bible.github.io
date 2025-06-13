---
layout: publication
title: 'Exploring Large Language Models For Specialist-level Oncology Care'
authors: Anil Palepu, Vikram Dhillon, Polly Niravath, Wei-hung Weng, Preethi Prasad, Khaled Saab, Ryutaro Tanno, Yong Cheng, Hanh Mai, Ethan Burns, Zainub Ajmal, Kavita Kulkarni, Philip Mansfield, Dale Webster, Joelle Barral, Juraj Gottweis, Mike Schaekermann, S. Sara Mahdavi, Vivek Natarajan, Alan Karthikesalingam, Tao Tu
conference: "Arxiv"
year: 2024
bibkey: palepu2024exploring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.03395"}
tags: ['Fine-Tuning', 'Responsible AI', 'Applications', 'Interpretability', 'Training Techniques', 'Pretraining Methods']
---
Large language models (LLMs) have shown remarkable progress in encoding
clinical knowledge and responding to complex medical queries with appropriate
clinical reasoning. However, their applicability in subspecialist or complex
medical settings remains underexplored. In this work, we probe the performance
of AMIE, a research conversational diagnostic AI system, in the subspecialist
domain of breast oncology care without specific fine-tuning to this challenging
domain. To perform this evaluation, we curated a set of 50 synthetic breast
cancer vignettes representing a range of treatment-naive and
treatment-refractory cases and mirroring the key information available to a
multidisciplinary tumor board for decision-making (openly released with this
work). We developed a detailed clinical rubric for evaluating management plans,
including axes such as the quality of case summarization, safety of the
proposed care plan, and recommendations for chemotherapy, radiotherapy, surgery
and hormonal therapy. To improve performance, we enhanced AMIE with the
inference-time ability to perform web search retrieval to gather relevant and
up-to-date clinical knowledge and refine its responses with a multi-stage
self-critique pipeline. We compare response quality of AMIE with internal
medicine trainees, oncology fellows, and general oncology attendings under both
automated and specialist clinician evaluations. In our evaluations, AMIE
outperformed trainees and fellows demonstrating the potential of the system in
this challenging and important domain. We further demonstrate through
qualitative examples, how systems such as AMIE might facilitate conversational
interactions to assist clinicians in their decision making. However, AMIE's
performance was overall inferior to attending oncologists suggesting that
further research is needed prior to consideration of prospective uses.
