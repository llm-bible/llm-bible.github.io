---
layout: publication
title: 'Investigating Automatic Scoring And Feedback Using Large Language Models'
authors: Gloria Ashiya Katuka, Alexander Gain, Yen-yun Yu
conference: "Arxiv"
year: 2024
bibkey: katuka2024investigating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2405.00602'}
tags: ['RAG', 'Efficiency and Optimization', 'Training Techniques', 'Quantization', 'Merging', 'Fine-Tuning', 'Reinforcement Learning', 'Pretraining Methods']
---
Automatic grading and feedback have been long studied using traditional
machine learning and deep learning techniques using language models. With the
recent accessibility to high performing large language models (LLMs) like
LLaMA-2, there is an opportunity to investigate the use of these LLMs for
automatic grading and feedback generation. Despite the increase in performance,
LLMs require significant computational resources for fine-tuning and additional
specific adjustments to enhance their performance for such tasks. To address
these issues, Parameter Efficient Fine-tuning (PEFT) methods, such as LoRA and
QLoRA, have been adopted to decrease memory and computational requirements in
model fine-tuning. This paper explores the efficacy of PEFT-based quantized
models, employing classification or regression head, to fine-tune LLMs for
automatically assigning continuous numerical grades to short answers and
essays, as well as generating corresponding feedback. We conducted experiments
on both proprietary and open-source datasets for our tasks. The results show
that prediction of grade scores via finetuned LLMs are highly accurate,
achieving less than 3% error in grade percentage on average. For providing
graded feedback fine-tuned 4-bit quantized LLaMA-2 13B models outperform
competitive base models and achieve high similarity with subject matter expert
feedback in terms of high BLEU and ROUGE scores and qualitatively in terms of
feedback. The findings from this study provide important insights into the
impacts of the emerging capabilities of using quantization approaches to
fine-tune LLMs for various downstream tasks, such as automatic short answer
scoring and feedback generation at comparatively lower costs and latency.
