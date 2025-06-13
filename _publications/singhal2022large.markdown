---
layout: publication
title: 'Large Language Models Encode Clinical Knowledge'
authors: Karan Singhal, Shekoofeh Azizi, Tao Tu, S. Sara Mahdavi, Jason Wei, Hyung Won Chung, Nathan Scales, Ajay Tanwani, Heather Cole-lewis, Stephen Pfohl, Perry Payne, Martin Seneviratne, Paul Gamble, Chris Kelly, Nathaneal Scharli, Aakanksha Chowdhery, Philip Mansfield, Blaise Aguera Y Arcas, Dale Webster, Greg S. Corrado, Yossi Matias, Katherine Chou, Juraj Gottweis, Nenad Tomasev, Yun Liu, Alvin Rajkomar, Joelle Barral, Christopher Semturs, Alan Karthikesalingam, Vivek Natarajan
conference: "Arxiv"
year: 2022
bibkey: singhal2022large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2212.13138"}
tags: ['Tools', 'RAG', 'Ethics and Bias', 'Prompting', 'Applications']
---
Large language models (LLMs) have demonstrated impressive capabilities in
natural language understanding and generation, but the quality bar for medical
and clinical applications is high. Today, attempts to assess models' clinical
knowledge typically rely on automated evaluations on limited benchmarks. There
is no standard to evaluate model predictions and reasoning across a breadth of
tasks. To address this, we present MultiMedQA, a benchmark combining six
existing open question answering datasets spanning professional medical exams,
research, and consumer queries; and HealthSearchQA, a new free-response dataset
of medical questions searched online. We propose a framework for human
evaluation of model answers along multiple axes including factuality,
precision, possible harm, and bias. In addition, we evaluate PaLM (a
540-billion parameter LLM) and its instruction-tuned variant, Flan-PaLM, on
MultiMedQA. Using a combination of prompting strategies, Flan-PaLM achieves
state-of-the-art accuracy on every MultiMedQA multiple-choice dataset (MedQA,
MedMCQA, PubMedQA, MMLU clinical topics), including 67.6% accuracy on MedQA (US
Medical License Exam questions), surpassing prior state-of-the-art by over 17%.
However, human evaluation reveals key gaps in Flan-PaLM responses. To resolve
this we introduce instruction prompt tuning, a parameter-efficient approach for
aligning LLMs to new domains using a few exemplars. The resulting model,
Med-PaLM, performs encouragingly, but remains inferior to clinicians. We show
that comprehension, recall of knowledge, and medical reasoning improve with
model scale and instruction prompt tuning, suggesting the potential utility of
LLMs in medicine. Our human evaluations reveal important limitations of today's
models, reinforcing the importance of both evaluation frameworks and method
development in creating safe, helpful LLM models for clinical applications.
