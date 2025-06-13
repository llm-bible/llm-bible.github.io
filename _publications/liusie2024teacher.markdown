---
layout: publication
title: 'Teacher-student Training For Debiasing: General Permutation Debiasing For Large Language Models'
authors: Adian Liusie, Yassir Fathullah, Mark J. F. Gales
conference: "Arxiv"
year: 2024
bibkey: liusie2024teacher
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2403.13590'}
tags: ['Ethics and Bias', 'Efficiency and Optimization', 'Distillation', 'Training Techniques']
---
Large Language Models (LLMs) have demonstrated impressive zero-shot
capabilities and versatility in NLP tasks, however they sometimes fail to
maintain crucial invariances for specific tasks. One example is permutation
sensitivity, where LLMs' outputs may significantly vary depending on the order
of the input options. While debiasing techniques can mitigate these issues, and
yield better performance and reliability, they often come with a high
computational cost at inference. This paper addresses this inefficiency at
inference time. The aim is to distill the capabilities of a computationally
intensive, debiased, teacher model into a more compact student model. We
explore two variants of student models: one based on pure distillation, and the
other on an error-correction approach for more complex tasks, where the student
corrects a single biased decision from the teacher to achieve a debiased
output. Our approach is general and can be applied to both black-box and
white-box LLMs. Furthermore, we demonstrate that our compact, encoder-only
student models can outperform their larger, biased teacher counterparts,
achieving better results with significantly fewer parameters.
